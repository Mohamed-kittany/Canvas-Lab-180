# Configuring a VPC

## Lab Overview

Amazon Virtual Private Cloud (Amazon VPC) enables the provisioning of a logically isolated section of the AWS Cloud. This lab provided an opportunity to launch AWS resources within a self-defined virtual network. Key elements include selecting IP address ranges, creating subnets, and configuring route tables and network gateways.

The primary goal was to construct a VPC and necessary network components essential for deploying resources like an Amazon EC2 instance.

## Objectives

Participants were tasked with achieving the following by the conclusion of the lab:

- Creation of a VPC incorporating both private and public subnets, alongside an internet gateway and a NAT gateway.
- Configuration of route tables associated with these subnets to manage local and internet-bound traffic via both an internet gateway and a NAT gateway.
- Deployment and utilization of a bastion server within the public subnet.
- Connection to an instance in the private subnet using the bastion server.

Additionally, an optional challenge was presented:
- Deployment of an Amazon EC2 instance within the private subnet and establishing its connectivity through the bastion server.

## Implementation Steps

1. **VPC Setup**: A VPC was configured with designated IP ranges.
2. **Subnet Creation**: One public and one private subnet were established within the VPC.
3. **Gateway Configuration**: An internet gateway and a NAT gateway were implemented to manage traffic flow.
4. **Route Table Configuration**: Route tables were updated to accurately direct local and internet-bound traffic through the appropriate gateways.
5. **Bastion Host Deployment**: A bastion host was deployed in the public subnet to enable secure SSH access to instances within the private subnet.

## Optional Challenge

- **EC2 Instance Deployment**: An EC2 instance was successfully launched in the private subnet, with connectivity verified using the bastion host.

## Technologies Used

- **Amazon VPC**
- **Amazon EC2**
- **Internet Gateway (IGW)**
- **Network Address Translation (NAT) Gateway**
- **Bastion Hosts**

## Conclusion

The lab effectively demonstrated how to configure a network within the AWS Cloud, emphasizing the importance of meticulous network design for managing access and connectivity of cloud resources.
