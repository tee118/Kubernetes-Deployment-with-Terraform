# Kubernetes Deployment with Terraform

## Introduction
This project utilizes Terraform to deploy a Kubernetes cluster and a PACMAN web app. The web app allows you to play PACMAN on your browser.

## Why Terraform with Kubernetes?
Terraform offers comprehensive management of resources, understands dependency relationships, and seamlessly integrates with Kubernetes.

## Prerequisites
- Cloud account with AWS
- AWS CLI
- kubectl
- Terraform
- Package managers: Chocolatey for Windows or Homebrew for macOS

## Installation (Windows)
1. Install AWS CLI: `choco install aws-cli`
2. Install kubectl: `choco install kubernetes-cli`
3. Login to AWS: `aws configure`

## Steps
1. Provision an EKS Cluster with Terraform:
   - Download files from GitHub
   - Run `terraform init`, `terraform validate`, and `terraform apply`
   - Configure kubectl with AWS credentials
   - Verify cluster and nodes
   
2. Deploy Web App and Database:
   - Download files from GitHub
   - Run `terraform init`, `terraform validate`, and `terraform apply`
   - Verify deployment and access the app
   
3. Manage Resources:
   - Adjust pod numbers in deployment files
   - Apply changes with `terraform apply`
   - Verify changes and refresh the page

## Summary
This project simplifies deploying a Kubernetes cluster and a PACMAN web app using Terraform. It ensures comprehensive management of resources, seamless integration with Kubernetes, and easy scalability.


## Read more

[Blog](https://teebaba.hashnode.dev/deploying-and-managing-a-web-app-in-kubernetes-with-terraform)