# Azure Terraform Web App Deployment

This repository contains Terraform configuration files for provisioning Azure resources required to deploy a web application using Azure App Service.

## Getting Started

To use these Terraform configurations, you'll need to set up an Azure account and install Terraform on your local machine.

1. Sign up for an Azure account if you don't have one already.
2. Install Terraform on your local machine by following the [official installation guide](https://learn.hashicorp.com/tutorials/terraform/install-cli).
3. Clone or fork this repository to your local machine.

## Usage

1. Customize the `main.tf` file with your desired configuration settings, such as resource names and locations.
2. Initialize Terraform by running `terraform init` in your terminal.
3. Review the execution plan by running `terraform plan` and verify that the proposed changes match your expectations.
4. Apply the changes to provision Azure resources by running `terraform apply`. 
5. Review the output to ensure that the resources were provisioned successfully.
6. Deploy your web application to the Azure App Service using the created resources.

For detailed instructions on using Terraform with Azure, refer to the [Terraform Azure Provider documentation](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
