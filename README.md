# Terraform Docker Task

## Objective
Provision a local Docker container using Terraform.

## Screenshots

### Terraform Apply Success
![Terraform Apply](screenshots/terraform-apply.png)

### Docker Container Running
![Docker PS](screenshots/docker-ps.png)

### Nginx Website
![Nginx Website](screenshots/nginx-website.png)

## Objective
Provision a local Docker container using Terraform.

## Steps
1. Installed Docker and Terraform.
2. Wrote `main.tf` to create an Nginx container.
3. Ran `terraform init`, `plan`, `apply`.
4. Verified container at http://localhost:8000.
5. Ran `terraform destroy` to clean up.

## Files
- `main.tf`: Terraform configuration file

## Learning
- Understanding of Infrastructure as Code (IaC)
- Basics of Terraform and Docker
- How to manage infrastructure using code
