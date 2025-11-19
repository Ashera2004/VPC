# VPC

## Name: Siddarth A S
## Reg No: 212224040316

## Ex.4 Deployment and configuration of a Private Cloud in AWS
## Aim:
To set up of a Private Cloud in AWS.

Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security. Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

## Procedure:
1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and compliance standards.

● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.

● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.

● Plan internet connectivity:
Determine if you need public internet access and how to configure it.

● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure environment.

3. Create Your VPC:
Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.  Choose "Create VPC": Initiate the VPC creation process. Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings. Create subnets: Define subnets within your VPC to isolate different parts of your network. Create route tables: Specify how traffic is routed within and outside the VPC.  Create security groups: Define access control rules for your resources.

4. Deploying Resources:
Launch EC2 instances: Create and launch virtual machines within your VPC.  Set up RDS instances: Deploy databases for your applications. Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables. Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

5.Managing and Monitoring:
Use AWS CloudWatch: Monitor your VPC and resources for performance and health. Configure logging and auditing: Track access and activity within your VPC for security and compliance. Implement security best practices: Regularly review and update your security configuration. Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

## Output:


<img width="1920" height="1200" alt="cc_ex4_igw4" src="https://github.com/user-attachments/assets/13eaf26a-b3b6-4662-a62b-9aa16ccd22a2" />
<img width="1920" height="1200" alt="cc_ex4_subnet_asso" src="https://github.com/user-attachments/assets/dc3c72b6-beab-47bb-b669-e78da4b0fc92" />
<img width="1920" height="1200" alt="cc_ex4_edit_routes" src="https://github.com/user-attachments/assets/0fde38c6-6000-4936-b7e3-70754af3c9d3" />
<img width="1920" height="1200" alt="cc_ex4_edit_routes2" src="https://github.com/user-attachments/assets/9ce46411-c848-45e3-a8e8-869e0aa94d9d" />
<img width="1920" height="1200" alt="cc_ex4_1" src="https://github.com/user-attachments/assets/af0cdc17-9ae0-42ab-818e-5a258c9913ba" />
<img width="1920" height="1200" alt="cc_ex4_2" src="https://github.com/user-attachments/assets/9e3af142-9c38-4119-b84d-98994d96c16f" />
<img width="1920" height="1200" alt="cc_ex4_3" src="https://github.com/user-attachments/assets/2b66366a-49df-438b-a454-a1ec6728c131" />
<img width="1920" height="1200" alt="cc_ex4_4" src="https://github.com/user-attachments/assets/374915b9-d57a-417f-be15-0a25ede15437" />
<img width="1920" height="1200" alt="cc_ex4_5" src="https://github.com/user-attachments/assets/38a15b88-b34a-4e9d-ba40-52ba61bd0f5c" />
<img width="1920" height="1200" alt="cc_ex4_6" src="https://github.com/user-attachments/assets/71b3a625-9a46-4f36-bdc3-3da4c01f4e55" />
<img width="1920" height="1200" alt="cc_ex4_igw1" src="https://github.com/user-attachments/assets/a870ff07-0a04-4082-9080-72836bab45a8" />
<img width="1920" height="1200" alt="cc_ex4_igw2" src="https://github.com/user-attachments/assets/687c2193-0adf-46ee-aa4e-8c7b289befa0" />
<img width="1920" height="1200" alt="cc_ex4_vpc1" src="https://github.com/user-attachments/assets/5d221bf6-6d35-4e66-a566-c92eca436180" />
<img width="1920" height="1200" alt="cc_ex4_vpc2" src="https://github.com/user-attachments/assets/1e11d7fb-c294-44fb-89b0-b57863f3ad15" />
<img width="1920" height="1200" alt="cc_ex4_igw3" src="https://github.com/user-attachments/assets/2c180f9d-afb0-42b9-83a0-396c2e617666" />



## RESULT:
The VPC is successfully created.


