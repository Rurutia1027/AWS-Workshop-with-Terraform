# AWS Infrastructure as Code with Terraform – Hands-On Workshop

This repository contains hands-on Terraform configurations and exercises based on the **"Learn By Doing: AWS Workshop with Terraform"** course from [KodeKloud](https://kodekloud.com). The goal is to provide a developer-centric, practical introduction to managing AWS infrastructure using Infrastructure as Code (IaC) principles with Terraform.

## 📦 What’s Inside

This repo is structured to reflect each stage of the course with modular and example-driven Terraform files for:

1. **Terraform & AWS Basics**
   - Initial setup for Terraform CLI and AWS CLI
   - Connecting Terraform to AWS
   - Deploying a basic EC2 instance

2. **Terraform with AWS Configuration**
   - Understanding and managing state
   - Using AWS S3 for remote backend storage
   - Secure credentials handling with AWS Secrets Manager

3. **HCL & Terraform Modules**
   - Writing reusable and maintainable Terraform code
   - Using variables, outputs, locals
   - Creating and using modules

4. **Terraform State Management**
   - State locking and migration
   - State file security and organization

5. **Advanced Terraform Techniques**
   - Workspaces for environment separation
   - Data sources and provisioners

6. **CI/CD with Terraform**
   - Automating deployments with AWS CodePipeline
   - Elastic Beanstalk deployment via Terraform

7. **Debugging & Troubleshooting**
   - Common errors in Terraform configs
   - Logging and diagnostics

8. **Final Project**
   - Deploy secure EC2 instances
   - Shared access to a centralized RDS database
   - Real-world implementation of previous topics

## 🛠 Requirements

- Terraform ≥ 1.0  
- AWS CLI configured with appropriate IAM credentials  
- An active AWS account  
- Basic knowledge of command-line usage

## 📂 Directory Structure

```bash
.
├── 01-terraform-aws-basics/
├── 02-remote-backend-and-credentials/
├── 03-writing-configurations/
├── 04-managing-state/
├── 05-advanced-features/
├── 06-cicd-automation/
├── 07-debugging/
├── 08-final-project/
└── README.md
```

## 📖 Reference
This repository is based on content provided by the KodeKloud AWS Workshop with Terraform course.


## 🧾 License
This repository is intended for personal learning and non-commercial use. Course content rights belong to KodeKloud.
