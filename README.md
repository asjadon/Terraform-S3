# Terraform AWS S3 Project

**Hands-on project** to create and manage an AWS S3 bucket using Terraform.

## Features

- Create S3 bucket
- Versioning enabled
- Server-side encryption (SSE-S3)
- Block public access
- Lifecycle rules for old objects

## Files

- `main.tf` – Terraform configuration  
- `variables.tf` – Input variables  
- `outputs.tf` – Terraform outputs  

## Usage

```bash
terraform init
terraform plan
terraform apply
# Type 'yes' to confirm
terraform destroy # To delete resources
