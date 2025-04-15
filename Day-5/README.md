# 🌿 Terraform Project

This project uses **Terraform** to manage infrastructure as code.

## 🛠️ Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) installed
- Cloud provider CLI configured (e.g., AWS CLI, Azure CLI)

## 🚀 Usage

1. **Initialize the working directory:**
   ```bash
   terraform init
2.**Format and validate the code:**
bash
terraform fmt
terraform validate
3.**Plan the infrastructure changes:**
bash
terraform plan
4.**Apply the configuration:**
bash
terraform apply
5.**Destroy the infrastructure (when needed):**
bash
terraform destroy

📁 **File Overview**
main.tf - Core infrastructure resources

variables.tf - Input variable definitions

terraform.tfvars - Actual values for variables

outputs.tf - Outputs from the infrastructure

provider.tf - Provider configuration

🔐 **Security**
Do not commit .tfstate or .terraform/ directories

Use .gitignore to prevent committing sensitive files

![terraform img](https://github.com/user-attachments/assets/12764ef4-52f5-422f-8568-f78f60b11a71)





![terraform code](https://github.com/user-attachments/assets/6a103885-8858-4e6a-868b-b7d044e58dca)
