# hybrid_cloud_task3
Create a VPC 
In that VPC create 2 subnet:- a) public subnet b) private subnet
Create a internet gateway and connect it to the public subnet. 
Create a routing table for Internet gateway ,update and associate it with public subnet. 
Launch an ec2 instance using wordpress AMI having the security group allowing port 80 in public subnet. Also attach the key to login into it. 
Launch an ec2 instance using MYSQL AMI with security group allowing port 3306 in private subnet, Also attach the key.
