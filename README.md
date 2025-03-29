# DevOps CI/CD Pipeline with Terraform, Jenkins, and Kubernetes

## Description
This repository demonstrates a simple CI/CD pipeline with Jenkins, using Terraform for infrastructure provisioning on AWS, and Kubernetes for deployment. The goal of this project is to automate the deployment of applications to the cloud.

## Prerequisites
- Terraform installed
- Jenkins installed with Docker support
- Kubernetes cluster set up (could be local or cloud-based)
- AWS CLI credentials configured

## Setup
### Step 1: Terraform Infrastructure Setup
1. Navigate to the `terraform/` directory.
2. Initialize Terraform:
   ```bash
   terraform init
