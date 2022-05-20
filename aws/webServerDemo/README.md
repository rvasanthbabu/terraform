# terraform httpd server setup in AWS using terraform

## Prerequisite
1. AWS free tier account
2. Terraform & AWS CLI installed in local

## Execution steps
1. Clone this repo to local
2. Update terraform.tfvars with Access & Secret keys
3. Execute ``` terraform init ```
4. Execute ``` terraform plan ```
5. Execute ``` terraform apply ```
6. The IP address of the web server will be displayed in console outup to validate in browser
7. Execute ``` terraform destroy ``` to delete all the AWS resources created by terraform.
