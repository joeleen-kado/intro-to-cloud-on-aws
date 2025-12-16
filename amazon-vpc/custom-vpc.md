# Create VPC
Name: my-vpc
IPv4 CIDR Block: 10.0.0.0/16

# Create Public and Private Subnets

Name: public-1a
Availability Zone: us-east-1a
IPv4 CIDR Block: 10.0.1.0/24

Name: public-1b
Availability Zone: us-east-1b
IPv4 CIDR Block: 10.0.2.0/24

Name: private-1a
Availability Zone: us-east-1a
IPv4 CIDR Block: 10.0.3.0/24

Name: private-1b
Availability Zone: us-east-1b
IPv4 CIDR Block: 10.0.4.0/24

# Create private route table

Name: private-rt
VPC: my-vpc
Subnet associations: Private-1A, Private-1B

# Create Internet Gateway

Name: my-igw
VPC: my-vpc