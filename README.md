# wordpress-on-AWS


VPC NETWORKING FOR WORDPRESS WEBSITE
List of Components

1- Create the VPC
2- create internet gateway and attach it to vpc 
3- Create 4 Subnets -- 2 Public & 2 Private 
4- Create 3 Route Tables -- 1 Public & 2 Private 
5- Associate the Public RT to 2 Public Subnets & the 2 Private RT to 2 Private Subnets 
6- Create 2 Elastic IP and Associate them to the 2 Nat Gateway
7- Create 2 Nat Gateway for the 2 private Subnets
