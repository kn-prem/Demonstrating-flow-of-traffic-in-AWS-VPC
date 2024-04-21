# Demonstrating-flow-of-traffic-in-AWS-VPC
Demonstrating how to configure network access control for an EC2 instance on AWS using custom VPCs, Security Groups, and Network Access Control Lists (NACLs).

1.Log in to AWS Management Console and navigate to VPC service.
2.Create a custom VPC with a specified IP address range and subnets.
3.Launch an EC2 instance within the custom VPC and public subnet.
4.SSH into the EC2 instance and update package repositories and install Python.
5.Start a simple HTTP server on Port 8000 using Python.
6.Open a web browser and navigate to http://<public_ip of EC2 instance>:8000 to verify access to the HTTP server.
7.Navigate to the Security Groups section in the EC2 service. Edit the inbound rules of the associated security group to allow traffic on Port 8000.
8.Access the Network ACLs section in the VPC service and can add the rules accordingly to allow or deny the traffic from a specific IP range.
