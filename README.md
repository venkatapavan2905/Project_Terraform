# Project_Terraform
Repository consists of Terraform scripts for AWS resources for the following architecture.

![image](https://github.com/venkatapavan2905/Project_Terraform/assets/138016465/09440de3-cc8d-4c65-9b44-5e2efaa971c2)



The VPC has public subnets and private subnets in two Availability Zones. Each public subnet contains a NAT gateway and a load balancer node. The servers run in the private subnets, are launched and terminated by using an Auto Scaling group, and receive traffic from the load balancer. The servers can connect to the internet by using the NAT gateway

