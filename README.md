# AWS EC2 Provisioning with Terraform and Ansible

![Ansible Workflow](https://github.com/MissSB/ansible/actions/workflows/ansible.yml/badge.svg)

This project provisions an AWS EC2 instance using Terraform, and configures it using Ansible.

## 🚀 What it Does

- Uses Terraform to create an EC2 instance on AWS
- Uses Ansible to install and configure packages on the EC2 instance
- Supports dynamic inventory using `inventory.ini`

## 📂 Project Structure

├── inventory.ini # Ansible inventory
├── main.tf # Terraform main configuration
├── outputs.tf # Terraform outputs
├── playbook.yml # Ansible playbook for configuration
├── variable.tf # Terraform variables
├── .gitignore # Git ignore file


## 🔧 Prerequisites

- Terraform installed
- Ansible installed
- AWS credentials configured (locally or via environment variables)

## ⚙️ How to Use

1. Initialize Terraform:
   ```bash
   terraform init
   terraform apply
ansible-playbook -i inventory.ini playbook.yml
# Updated
# Trigger Actions
# Changed a thing
# Changed another thing
# Changed Ansible Format
