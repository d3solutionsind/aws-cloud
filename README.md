# aws-cloud

**AWS-Devops**
AWS zero to hero repo for devops engineers to learn AWS . This repo includes projects, presentations,
interview questions and real time examples. Each day's class will provide real-time knowledge on AWS services, 
allowing you to apply what you've learned and gain practical skills in working with AWS in a DevOps context.

**Topic 1: Introduction to AWS**
You will learn what is private and public cloud. Why companies are moving to public cloud, what are the advantages of moving to cloud.
Also, you will be introduced to the basics of AWS, including the core services and their significance in DevOps practices. 
Finally learn how to set up an AWS account and navigate the AWS Management Console.

**Topic 2: IAM (Identity and Access Management)**
You will explore IAM, which is used for managing access to AWS resources. You'll learn how to create IAM users, groups, and roles, 
and how to apply permissions and security best practices to ensure proper access control.

**Topic 3: EC2 Instances**
You'll dive into EC2, which provides virtual servers in the cloud. You'll learn how to launch EC2 instances,
connect to them using SSH, and understand key concepts such as instance types, security groups, and key pairs.
Your First AWS Project: Deploy a simple web application(such as jenkins) on the EC-2 instance and access the application from outside AWS.

**Topic 4: AWS Networking (VPC)**
You'll explore AWS networking concepts, with a specific focus on VPC (Virtual Private Cloud). 
You'll learn how to create and configure VPCs, subnets, and route tables, 
enabling you to design and manage the network infrastructure for your applications.

**Topic 5: AWS Security**
This day emphasizes security best practices in AWS. You'll learn how to implement security measures such as security groups, 
network ACLs (Access Control Lists), and IAM policies to ensure the confidentiality, integrity,
and availability of your AWS resources.

**Topic 6: AWS Route 53**
Project: Configure and manage a domain name using Route 53. You'll register a domain,
set up DNS records, and explore advanced features such as health checks, routing policies, and DNS-based failover.

**Topic 7: Secure VPC Setup with EC2 Instances**
Project:
•	Design and configure a VPC: Create a VPC with custom IP ranges. Set up public and private subnets.
Configure route tables and associate subnets.
•	Implement network security: Set up network access control lists (ACLs) to control inbound and outbound traffic.
Configure security groups for EC2 instances to allow specific ports and protocols.
•	Provision EC2 instances: Launch EC2 instances in both the public and private subnets. 
Configure security groups for the instances to allow necessary traffic.
Create and assign IAM roles to the instances with appropriate permissions.
•	Networking and routing: Set up an internet gateway to allow internet access for instances in the public subnet.
Configure NAT gateway or NAT instance to enable outbound internet access for instances in the private subnet. 
Create appropriate route tables and associate them with the subnets.
•	SSH key pair and access control: Generate an SSH key pair and securely store the private key.
Configure the instances to allow SSH access only with the generated key pair. 
Implement IAM policies and roles to control access and permissions to AWS resources.
•	Test and validate the setup: SSH into the EC2 instances using the private key and verify connectivity. 
Test network connectivity between instances in different subnets. Validate security group rules and network ACL settings.
By implementing this project, you'll gain hands-on experience in setting up a secure VPC with EC2 instances,
implementing networking and routing, configuring security groups and IAM roles, and ensuring proper access control. 
This project will provide a practical understanding of how these AWS services work together to create a secure 
and scalable infrastructure for your applications.

**Topic 8: Amazon S3**
This day focuses on Amazon S3, a scalable object storage service.
You'll learn how to create S3 buckets, upload and download objects,
and organize data using S3 features like versioning, lifecycle policies, and access control.

**Topic 9: AWS CloudFormation**

This day introduces Infrastructure as Code (IaC) using AWS CloudFormation.
You'll learn how to create CloudFormation templates to automate the provisioning of resources, manage stacks,
and ensure consistent infrastructure across deployments.
Project: You'll work on creating a CloudFormation template that provisions a fully configured application stack, 
including EC2 instances, networking components, and security groups.

**Topic 10: AWS CodeCommit**
This day focuses on AWS CodeCommit, a managed source control service.
You'll learn how to set up a Git repository in CodeCommit,
collaborate with team members, and manage version control of your codebase.
Project: You'll configure a CodeCommit repository for a team project, 
including setting up access control and collaboration workflows.

**Topic 11: AWS CodePipeline**
You'll dive into AWS CodePipeline, a fully managed continuous delivery service.
You'll learn how to build end-to-end CI/CD pipelines by configuring source, 
build, and deployment stages, automating the entire software release process.
Project: You'll create a CI/CD pipeline using CodePipeline for an application deployment,
including source code integration, build, and automatic deployment to a target environment.

**Topic 12: AWS CodeBuild**
This day focuses on AWS CodeBuild, a fully managed build service.
You'll learn how to configure build projects in CodeBuild, define build specifications,
and perform build and testing processes.
Project: You'll configure and run CodeBuild for a project, 
including defining build specifications and integrating with other AWS services.

**Topic 13: AWS CodeDeploy**
You'll explore AWS CodeDeploy, a service for automating application deployments to various compute environments.
You'll learn how to create deployment groups, configure deployment strategies,
and perform automatic rollbacks if necessary.
Project: You'll implement a Blue/Green deployment strategy for a sample application using CodeDeploy, 
ensuring zero-downtime deployments and easy rollback options.

**Topic 14: AWS CloudWatch**
This day focuses on monitoring AWS resources using AWS CloudWatch. You'll learn how to create alarms, 
set up notifications, and collect metrics to gain insights into the health
and performance of your applications and infrastructure

**Topic !5: AWS Lambda**
This day introduces serverless computing with AWS Lambda. You'll learn how to create and deploy serverless functions, 
trigger them based on events, and leverage Lambda to build scalable and event-driven architectures.

**Topic 16: AWS CloudWatch Events and EventBridge**
This day focuses on AWS CloudWatch Events and EventBridge, services for event-driven architectures.
You'll learn how to create event rules, configure event targets, and build serverless event-driven workflows.
Project: You'll build a serverless event-driven workflow using CloudWatch Events and EventBridge,
demonstrating the integration and automation of different AWS services based on events.

**Topic 17: AWS CloudFront**
If you've never heard of CDN or CloudFront before, don't worry, 
we will start from scratch and gradually build up your understanding. 
By the end, you'll be well-versed in these technologies.
Project: You'll configure a s3 bucket to host a static website and learn how to serve the requests to this website through CDN that is AWS Cloud Front.

**Topic !8: AWS ECR (Elastic Container Registry)**
You'll explore AWS ECR, a fully managed container registry for storing and managing container images. 
You'll learn how to push and pull Docker images to and from ECR, enabling seamless integration with ECS and other container services.

**Topic 19: AWS ECS (Elastic Container Service)**
This day focuses on AWS ECS, a fully managed container orchestration service. 
You'll learn how to run and manage containers using ECS, including creating task definitions,
managing services, and scaling with auto-scaling capabilities.
Project: You'll deploy a multi-container application using ECS, configure auto-scaling policies, 
and ensure high availability and efficient resource utilization.

**Topic 20: AWS EKS (Elastic Kubernetes Service)**
This day introduces AWS EKS, a fully managed Kubernetes service.
You'll learn how to deploy and manage Kubernetes clusters using EKS,
including launching worker nodes, configuring networking, and deploying applications using Kubernetes manifests.
Project: You'll deploy a sample application on EKS using Kubernetes manifests,
demonstrating the capabilities of running containerized applications on a managed Kubernetes service.

