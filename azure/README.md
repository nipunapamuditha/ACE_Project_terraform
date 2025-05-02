# 🟦 Azure Free Tier VM - Terraform

This module provisions a **Standard_B1s Ubuntu VM** using Terraform on Microsoft Azure, using Free Tier eligible resources.

---

## 🔧 Pre-requisites

- Azure Free Tier account
- Azure CLI configured (`az login`)
- SSH key pair on your local system

---

## 📦 Setup

### 1. Configure Variables (optional)

You can override defaults in a `terraform.tfvars` file:
```hcl
admin_username       = "azureuser"
ssh_public_key_path  = "~/.ssh/id_rsa.pub"
location             = "eastus"
