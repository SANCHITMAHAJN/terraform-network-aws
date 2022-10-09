# terraform-network-aws
This Terraform project (guided) configures VPCs, subnet, gateways, provides an elastic IP to assign to an EC2 instance in AWS,


This script does the following:

	Creates a Production subnet
	Sets up Gateway and Route Table
	Creates a subnet and associates with the route table
	Creates security group to allow ports 22,80, 443
	Sets up a network interface to be used 
	Assign a static IP (10.1.1.50) to the network interface
	Start a .t2 micro Ubuntu EC2 instance
	Set up  a web-server on the instance



