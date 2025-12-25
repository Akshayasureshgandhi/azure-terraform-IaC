
# Automated Azure Infrastructure Provisioning using Terraform

This project provisions a Linux Virtual Machine on Microsoft Azure using Terraform.
It demonstrates Infrastructure as Code (IaC) best practices, Azure resource provisioning, and Git version control.

# Architecture Overview
The Terraform configuration creates the following Azure resources:
<img width="1359" height="944" alt="image" src="https://github.com/user-attachments/assets/0fb8c04f-46d1-4747-b252-92a033b56999" />

* Resource Group
* Virtual Network (VNet)
* Subnet
* Network Interface (NIC)
* Public IP Address
* Linux Virtual Machine (Ubuntu)

All resources are created within a single Azure Resource Group.
