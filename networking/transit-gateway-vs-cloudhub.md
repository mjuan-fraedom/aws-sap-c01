# Transit Gateway vs CloudHub

### Transit Gateway
* An actual AWS Service
* Connects VPC and on-prem together
* Used to allow transitive peering (a VPC limitation) between VPCs


### CloudHub
* Not an actual AWS Service
* More like a strategy. You can use a Transit Gateway or your own EC2 Instance router to enable transitive peering
* Uses an Amazon VPC virtual private gateway with multiple customer gateways
* Connects VPC and on-prem together
