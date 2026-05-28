# Azure Terraform Infrastructure Project

This project demonstrates Infrastructure as Code (IaC) using Terraform to automate the deployment of Azure cloud infrastructure.

The goal of this project was to build foundational Terraform skills while learning how cloud resources can be provisioned, managed, and deployed through code instead of manually creating resources through the Azure portal.

---

# Technologies Used

## Cloud Platform
- Microsoft Azure

## Infrastructure as Code
- Terraform

## Operating System
- Ubuntu Linux

## Cloud Resources
- Azure Virtual Machine
- Azure Resource Group
- Azure Virtual Network
- Azure Subnet
- Azure Network Security Group
- Azure Public IP

---

# Project Objectives

- Learn Terraform fundamentals
- Understand Infrastructure as Code concepts
- Automate Azure resource deployment
- Deploy cloud infrastructure through configuration files
- Learn Terraform workflow and state management
- Practice Linux and cloud administration skills

---

# What This Project Demonstrates

## Infrastructure as Code (IaC)

Instead of manually clicking through the Azure portal, infrastructure is defined using Terraform configuration files.

Example resources created:
- Virtual Machines
- Networking
- Security Rules
- Public IPs

---

# Terraform Workflow

The project used the standard Terraform workflow:

## Initialize Terraform

```bash
terraform init
```

## Preview Infrastructure Changes

```bash
terraform plan
```

## Deploy Infrastructure 

```bash
terraform apply 
```
```bash
terraform apply -auto-approve
```

## Destroy Infrastructure 

```bash
terraform destory
```
```bash
terraform destory -auto-approve
```


## Skills Demonstrated 

- Terraform Fundamentals
- Infrastructure as Code (IaC)
- Azure Cloud Infrastructure
- Linux Administration
- Cloud Networking
- Azure Resource Deployment
- Network Security Groups
- Virtual Machine Provisioning
- Cloud Automation
- Command Line Usage

## Future Improvements
- Multi-VM deployments
- Load balancers
- Terraform modules
- Remote Terraform state storage
- CI/CD integration
- Docker container deployments
- Kubernetes infrastructure
- Azure monitoring and logging

## Learning Outcomes 

This project helped build foundational cloud engineering and DevOps skills by demonstrating how modern cloud infrastructure can be deployed and managed entirely through code using Terraform.
