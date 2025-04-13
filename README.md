# VPC-Terraform

This Terraform project creates a custom VPC in AWS with the following components:
- VPC
- Public & Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Route Table Associations

---

## Prerequisites
- AWS Account
- Terraform installed
- AWS CLI configured with profile `naveed1-aws`

---

## Usage

### Initialize Terraform
```bash
AWS_PROFILE=naveed1-aws
terraform init
terraform plan
terraform apply
terraform state list
terraform destroy


