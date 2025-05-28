# 🚀 AWS VM Provisioning with Terraform

This project demonstrates how to **provision a Virtual Machine (EC2 instance) on AWS using Terraform**, following best practices for dynamic configuration, automation, and output usage. It's designed as a hands-on learning exercise based on a tutorial by [Nicholas Jackson](https://github.com/nicholasjackson/demo-terraform-aws-vm), to solidify Infrastructure as Code (IaC) concepts.

---

## 🎯 What You'll Learn

By completing this project, you will:

- ✅ Create an **EC2 instance** (Virtual Machine) in AWS using Terraform
- ✅ Use **variables** and **data sources** to make configuration dynamic
- ✅ Use **cloud-init scripts** to provision applications during boot
- ✅ Output key information such as public IP, instance ID, etc.
- ✅ Understand **Terraform workflow**: init → plan → apply → destroy

---

## 🛠️ Tech Stack

| Tool       | Purpose                       |
| ---------- | ----------------------------- |
| Terraform  | Infrastructure as Code (IaC)  |
| AWS        | Cloud infrastructure provider |
| Cloud-Init | EC2 boot-time provisioning    |

---

## 🧱 Folder Structure

```bash
terraform-aws-vm/
├── main.tf            # Main infrastructure definition
├── variables.tf       # Variables and types
├── outputs.tf         # Useful resource outputs
├── terraform.tfvars   # Actual variable values
├── user_data.sh       # Cloud-init script for EC2
└── README.md          # This file
```
