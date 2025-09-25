# Terraform Docker Task

## Objective
Provision a local Docker container using Terraform.

## Screenshots

### Terraform Apply Success
![Terraform Apply](https://github.com/imyadavankit/terraform-docker-task/blob/main/Screenshot%202025-09-25%20114731.png?raw=true)

### Docker Container Running
![Docker PS](https://github.com/imyadavankit/terraform-docker-task/blob/main/Screenshot%202025-09-25%20121217.png?raw=true)

### Nginx Website
![Nginx Website](https://github.com/imyadavankit/terraform-docker-task/blob/main/Screenshot%202025-09-25%20121005.png?raw=true)

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
