# Secure, Repeatable AWS Environments Using Terraform

## 1. Business Case

The goal is to create secure and repeatable development, staging, and production environments using Infrastructure as Code rather than manually creating and configuring cloud resources.

Manual configuration can lead to inconsistent environments, human error, and difficulty reproducing infrastructure.

## 2. Project Objective

Use Terraform to define AWS infrastructure in code so that network, security, and compute configurations can be reviewed, validated, and reproduced.

## 3. Planned Infrastructure

- **VPC:** The AWS virtual network.
- **Subnets:** Network segments within the VPC.
- **Security Groups:** Rules controlling traffic to AWS resources.
- **Private EC2 instance:** A Linux virtual machine designed without direct public exposure.
- **Amazon S3 remote state:** Remote storage for Terraform state, with appropriate access controls.
- **Environment configurations:** A repeatable approach to development, staging, and production.

## 4. Tools

- Terraform
- AWS
- Git and GitHub
- Ubuntu on WSL

## 5. Security and Cost Constraints

The project targets a $0 budget. AWS deployment will only be considered after checking current pricing, account eligibility, and possible charges. If deployment cannot be safely verified as free, I will use local validation and document the limitation.

Secrets and credentials must not be committed to GitHub.

## 6. Progress

### Day 1

- Verified the Ubuntu environment.
- Installed Terraform and checked its version.
- Verified Git is installed.
- Began defining the business case and project scope.

## 7. Results

Implementation and testing results will be added as the project progresses. Only verified work will be reported as completed.
