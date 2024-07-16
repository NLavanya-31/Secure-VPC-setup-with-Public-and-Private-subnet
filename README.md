# Secure-VPC-setup-with-Public-and-Private-subnet
This project's overview is depicted in the diagram below. The setup revolves around a Virtual Private Cloud (VPC) featuring both public and private subnets, thoughtfully distributed across two Availability Zones to ensure reliability.

Within each public subnet, there's a NAT gateway to facilitate outbound internet connectivity and a load balancer node for effective traffic distribution.

On the other hand, the project's servers reside in the private subnets. Their deployment and termination are automated through an Auto Scaling group, allowing them to dynamically adapt to workload changes. These servers play a pivotal role in receiving traffic from the load balancer and can access the internet through the NAT gateway when necessary
![vpc-public-private-subnets-architecture](https://github.com/NLavanya-31/Secure-VPC-setup-with-Public-and-Private-subnet/assets/155809688/2b5f8b55-2760-46cb-b66b-5ca06d454929)
