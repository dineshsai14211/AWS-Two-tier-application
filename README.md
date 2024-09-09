# AWS-Two-tier-application
## 1)Infrastructure Overview:-
      Developed a two-tier AWS VPC application with:
      Two Public Subnets housing an Application Load Balancer for external traffic routing.
      Two Private Subnets with EC2 instances deployed through Auto Scaling Group for application processing.
      Utilized a Bastion Host in the Public Subnet for secure access to EC2 instances in the Private Subnet.
      Implemented NAT Gateway and Internet Gateway for outbound internet access.

## 2)Networking Components:
      Configured a VPC with:
      Two Public Subnets facilitating external communication.
      Two Private Subnets for internal application processing.
      Implemented NAT Gateway for private subnet internet access.
      Employed Internet Gateway for public subnet internet connectivity.

## 3)Load Balancing and Scaling:
    Integrated an Application Load Balancer in the Public Subnet for distributing external requests to EC2 instances in the Private Subnet.
    Utilized Auto Scaling Group for dynamic scaling of EC2 instances based on demand.

## 4)Secure Access with Bastion Host:
    Deployed a Bastion Host in the Public Subnet to enable secure access to EC2 instances in the Private Subnet, which lack public IP 
    addresses.

## 5)Gateway Connectivity:
    Established connectivity to the internet via an Internet Gateway for resources in the Public Subnet.
    Implemented NAT Gateway for secure outbound internet access from resources in the Private Subnet.

# Image of Two-tier application
  ![Screenshot](https://github.com/dineshsai14211/AWS-Two-tier- application/blob/main/Implementation%20screenshots/two%20tier%20aws%20architecture.png)


