# Terraform Amazon EKS Cluster Provisioning

This repository contains Terraform code to automate the provisioning of an Amazon Elastic Kubernetes Service (EKS) cluster on AWS. It simplifies Kubernetes cluster management by using Terraform’s declarative infrastructure as code approach.

## Why Use Amazon EKS with Terraform?

- Simplified management of Kubernetes control plane and worker nodes  
- Scalable infrastructure with managed node groups  
- Integration with Kubernetes standard tooling (kubectl, kubeconfig)  
- Reliable state management with Terraform using S3 backend  

## Prerequisites

- Terraform installed  
- AWS CLI installed and configured with appropriate IAM permissions  
- An S3 bucket for storing Terraform state  

## Terraform Configuration Highlights

- VPC with public and private subnets  
- EKS cluster with two managed node groups  
- Terraform backend configured to use S3 for state management  
- Variables for AWS region and cluster name  
- Outputs for cluster info and endpoints  

## Learn More

For a complete step-by-step guide, code explanations, and best practices, check out the full article here:

👉 [Provisioning Amazon EKS Cluster with Terraform (Medium)](https://medium.com/devops-dev/setting-up-amazon-eks-cluster-using-terraform-11c11072d414)

