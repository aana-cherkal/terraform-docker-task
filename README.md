# Terraform Docker Task

## Objective
Provision a local Docker container using Terraform, demonstrating Infrastructure as Code (IaC).

## Tools
- Terraform v1.5.6
- Docker
- Linux (EC2 instance)

## Description
This project uses Terraform to automate the creation of a Docker container running Nginx. The steps include:

1. Initializing Terraform (`terraform init`)
2. Planning the infrastructure (`terraform plan`)
3. Applying the configuration (`terraform apply`)
4. Destroying the infrastructure (`terraform destroy`)

Terraform manages both the Docker image and the container.

## Files
- `main.tf` — Terraform configuration to create Docker image and container
- `terraform-init.log` — Logs from `terraform init`
- `terraform-plan.log` — Logs from `terraform plan`
- `terraform-apply.log` — Logs from `terraform apply`

