# AWS-cloudformation script for Highly Available Bastion Host
The task is to code highly available Bastion Host (linux ec2 instance) with the requirements below
- You need to be able to choose VPC, Subnets, Instance type, Instance AMI ID and Key Name for the host
- After termination, the host has to be automatically relaunched in a different AZ
- The host has to have the same puplic IP address, even after termination
- The host has to have the bare minimum permissions it needs to perform its work (The principle of least privilege)
- All new resources have to be taged and/or named to let us know that they belong to this project
