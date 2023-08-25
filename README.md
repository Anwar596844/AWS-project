# AWS-project
Today Project is AWS Project With Name Is VPC with public-private subnet in Production.

This example demonstrates how to create a VPC that you can use for servers in a production environment.

To improve resiliency , you deploy the servers in two Availability Zones , by using an Auto SCaling group and an Application Load Balancer. For additional security, you deploy the servers in private subnets.
The servers recieve requests through the load balancer. The servers can connect to the internet by using a NAT gateway. To improve resiliency , you deploy the NAT gateway.To improve resiliency,you deploy the
the NAT gateway in both Avaliabilty Zone.
