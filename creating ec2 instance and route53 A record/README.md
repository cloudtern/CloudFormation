Cloudformation script for creating a EC2 instance and creating a A record in private hosted zone.
# Description
We at CloudTern use cloudFormation very rigorously to create infrastructure on AWS. The best advantage of using cloudformation service is, it eliminates the need to use the management console or Web Console. If anything goes wrong in creating infrastucture, cloudformation provides the flexiblity to rollback the infrastructure it has created.

with this cloudformation script we have launched the Ec2Instance and created the A record set in the given hosted zone( Route53 )

After launching the script, AWS account will consists of the following elements:

* One EC2 Instance.
* A record with private IPv4 of the instance we have launched before in selected hosted zone.