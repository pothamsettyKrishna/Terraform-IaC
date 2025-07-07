# Terraform-IaC

Terraform is an infrastructure as code (IaC) tool that allows users to define and provision a datacenter infrastructure using a declarative configuration language. 

#### API as Code

API as Code is a concept, using which you can automate any provider like AWS, GDP, Azure. 


### Adavantages of Terraform

1. Manage any infrastructure
2. Track your infrastructure
3. Automate changes
4. Standardize configurations
5. Collaborate

### Commands

1. terraform init -> Initialize
2. terraform plan -> Dry Run
3. terraform apply
4. terraform destroy

### Terraform State files

Terraform state files are crucial for Terraform's operation, acting as a record of the infrastructure it manages. 

They map the resources defined in your Terraform configuration to their real-world counterparts, enabling Terraform to track changes, plan updates, and avoid unnecessary recreation of resources.


### Problems with terraform

1. State file is single source of truth.
2. Manual changes to the cloud provider cannot be identified and auto-corrected.
3. Not a GitOps friendly tool.
4. Can be very complex and difficult to manage.
5. Trying to postion as a configuration management tool as well.


