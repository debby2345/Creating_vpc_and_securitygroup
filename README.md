# Creating_vpc_and_securitygroup
This project document the process of Creating_vpc_and_securitygroup
### VPC Creation
Choose "VPC and more" under VPC settings
##### Named the VPC "VPC Project"
Selected IPv4 as the IP address family,
Choose "10.0.0.0/16" as the IPv4 CIDR block,
Selected "Amazon provided IPv6 CIDR block" for IPv6,
Choose the default tenancy option,
Below is the image
![vpc Creation](/VPC_1.PNG)

### Configure VPC Settings
Selected 2 availability zones,
Chooose 2 subnets,
Selected 2 public subnets and 2 private subnets,
Used default subnet CIDR blocks,
Below is the image
![vpc Creation](/VPC_2.PNG)

### Configure NAT Gateway and Internet Gateway
Choose "1 NAT gateway per AZ",
Selected "Yes" for internet gateway,
Choose "S3 Gateway" for VPC endpoint,
Enabled DNS resolution,
Below is the image
![vpc Creation](/VPC_3.PNG)

### VPC Successfully Created
Successfully created the VPC.
![vpc Creation](/VPC_4.PNG)
![vpc Creation](/VPC_5.PNG)
![vpc Creation](/VPC_6.PNG)
