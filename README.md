AWS VPC Peering Project
Objective
Design and implement AWS VPC Peering between two VPCs and verify private connectivity.

->Architecture
VPC A
1.CIDR: 10.10.0.0/16
2.Public Subnet: 10.10.1.0/24
3.Private Subnet: 10.10.2.0/24

VPC B
1.CIDR: 10.20.0.0/16
2.Private Subnet: 10.20.1.0/24

EC2 Instances
1.ewb-bastion (10.10.1.10)
2.ewb-app-a (10.10.2.10)
3.ewb-app-b (10.20.1.10)

AWS Services Used
1.VPC
2.Subnets
3.Route Tables
4.Internet Gateway
5.Security Groups
6.EC2
7.VPC Peering

Result
Successfully established private connectivity between workloads across two VPCs using AWS VPC Peering.

