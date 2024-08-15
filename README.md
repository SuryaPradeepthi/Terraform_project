# Terraform_project
Automated EKS Deployment with Terraform and AWS

In this project, I will use both a local machine and a virtual machine. Terraform is installed on the virtual machine. We will configure Terraform to connect to an AWS account. When someone executes the Terraform project connected to the AWS account, it will create a VPC. Within the VPC, it will create an EKS cluster with auto-scaling configured to maintain a minimum or desired state of 2 EC2 instances. The maximum number of nodes will be set to 6 to accommodate increased traffic. EC2 instances will be used as worker nodes, starting with 2 instances, and can scale up to 6 instances as needed. Additionally, security groups will be created to secure and manage access.


