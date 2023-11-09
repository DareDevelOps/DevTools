# Terraform Backend

## Azure
Need to deploy to different backend definitions. One for an interactive deployment and one for CI/CD deployment

## basic configuration variables for backend tf
- Storage account name
- resource_group_name  = "RG-DDOps-Infra"
- storage_account_name = "saddopsinfra"
- container_name       = "solname"
- key                  = "sn.terraform.tfstate"

The -container name will be named after the solution
The key should indicate the environment possibly 
sn =  Solution Name
env = Enviroment Dev, Stage, Prod etc.
example: mysolution.prod.terraform.tfsate