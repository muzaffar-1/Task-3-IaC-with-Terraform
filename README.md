# Task-3-IaC-with-Terraform
# Terraform Docker Task

## Task Objective
- Pull a private Docker Hub image `muzaffar81/nodejs-demo-app`.
- Run it as a Docker container using Terraform on a Linux system (EC2).

## Prerequisites
- Docker installed and running.
- Terraform installed.
- Docker Hub account with access token.

## Files
- `main.tf` → Terraform configuration to pull image and create container.
- `variables.tf` → Variables for Docker Hub username and access token.
- `terraform.tfvars` → Set your username and access token.

## Terraform Steps
1. Initialize Terraform:
```bash
terraform init
2.Check execution plan:
  terraform plan
3.Apply the configuration:
  terraform apply
   Type yes when prompted.

## Verification
1.Check running container:
docker ps
2.Check pulled image:
docker images

Notes
Docker image is pulled from private Docker Hub repo.
Container exposes port 3000 (as defined in Terraform).

https://github.com/user-attachments/assets/818af31e-a760-4d9e-b12b-8f187c88e3c5
https://github.com/user-attachments/assets/c9a57ea2-3b60-4c29-8db6-ce6d28b1933e




