# aws-vpc-bastion-host-lab
# AWS VPC and Bastion Host Architecture Lab

This project demonstrates the design and implementation of a secure AWS network architecture. The environment consists of a custom VPC with public and private subnets across multiple Availability Zones, an Internet Gateway, a NAT Gateway for outbound internet access from private resources, a Bastion Host for secure administration, and EC2 instances deployed in private subnets.

The project validates secure access patterns by connecting from a local machine to a Bastion Host in a public subnet and then securely accessing a private EC2 instance using SSH.

## Technologies Used

* Amazon VPC
* Amazon EC2
* Internet Gateway
* NAT Gateway
* Route Tables
* Security Groups
* SSH
* Ubuntu Linux

## Architecture Highlights

* Custom VPC (`10.0.0.0/16`)
* 2 Public Subnets
* 2 Private Subnets
* Public and Private Route Tables
* Internet Gateway for public resources
* NAT Gateway for private subnet internet access
* Bastion Host for secure administration
* Private EC2 instance accessible only through the Bastion Host
