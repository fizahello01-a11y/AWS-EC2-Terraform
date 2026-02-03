# AWS-EC2-Terraform
EC2 creation using AWS console and Terraform
# AWS EC2 Setup Using Terraform

AWS (Amazon Web Services):
AWS is a cloud platform provided by Amazon that allows us to use servers,storage and networking services over the internet.Instead of owning physical servers we can create and manage resources only when we need them.

EC2 (Elastic Compute Cloud):
EC2 is a service that provides virtual servers called instances.These instances can be used to run applications,websites or backend services.

Region:
A region is a physical location where AWS has data centers.Each region is isolated from others. 

Availability Zone:
An availability zone is a data center within a region.Each region has multiple availability zones to provide high availability and fault tolerance.

VPC (Virtual Private Cloud):
A VPC is a private virtual network inside AWS where resources like EC2 instances are launched. It allows us to control IP ranges,subnets,routing and security.VPC helps in keeping resources isolated and secure.

Subnet:
A subnet is a smaller network inside a VPC.Subnets can be public or private.Public subnets allow internet access while private subnets are used for internal resources.

Security Group:
A security group works like a firewall for EC2 instances.It controls inbound and outbound traffic using rules.

IAM (Identity and Access Management):
IAM is used to manage users, roles and permissions in AWS.It ensures that only authorized users and services can access AWS resources.

Key Pair:
A key pair is used to securely connect to an EC2 instance using SSH.

EC2 Creation Using AWS Console 
steps followed:
1. Logged into the AWS Management Console.
2. Navigated to the EC2 service.
3. Clicked on Launch Instance.
4. Selected Amazon Linux as the AMI.
5. Chose t3.micro instance type.
6. Created a new key pair.
7. Configured security group to allow SSH access.
8. Launched the EC2 instance successfully.

EC2 Creation Using Terraform
Steps Followed:
1. Installed Terraform on my PC.
2. Configured AWS CLI using aws configure
3. Created a folder for Terraform EC2 configuration
4. Wrote Terraform configuration in main.tf
5. Initialized Terraform
6. created the EC2 instance

Terraform Commands Used:
terraform init
terraform plan
terraform apply
