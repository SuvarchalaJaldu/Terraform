# AWS EC2 Automation using Terraform and Jenkins

This project is centered around automating the deployment of AWS EC2 instances using Terraform. By utilizing Terraform, the project aids in the efficient management of cloud resources. Moreover, the integration with Jenkins ensures a seamless continuous integration and deployment process.


## Features

- **Automated AWS EC2 Deployment**: Use Terraform scripts to easily spin up EC2 instances.
  
- **Jenkins Integration**: Ensures continuous integration and deployment, making cloud management a breeze.

## Getting Started

1. Clone this repository.
2. Ensure you have Terraform and Jenkins installed and set up.
3. Update the Terraform configuration files with your AWS credentials or configure AWS CLI.
4. Deploy using Terraform commands or through Jenkins pipeline.

## Jenkins setup:

Configure your Jenkins server to point to this repository.
Create a new Jenkins pipeline and use the provided Jenkinsfile.

## Usage

1. Initialize Terraform:
   ```bash
   terraform init

2. Plan and apply your configurations:

```bash
terraform plan
terraform apply
