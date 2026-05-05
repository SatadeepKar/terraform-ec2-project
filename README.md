# Terraform EC2 Project

## Objective

To learn Terraform basics and create an AWS EC2 instance using Infrastructure as Code.

## Steps Performed

1. Installed Terraform and AWS CLI
2. Configured AWS using `aws configure`
3. Created a Terraform configuration file (`main.tf`)
4. Initialized Terraform:

   ```
   terraform init
   ```
5. Planned infrastructure:

   ```
   terraform plan
   ```
6. Applied configuration:

   ```
   terraform apply
   ```
7. Successfully created EC2 instance and obtained public IP

## Resources Created

* AWS EC2 Instance (Amazon Linux)
* Instance Type: t3.micro (used instead of t2.micro due to AWS restriction)
* Tag: Terraform-Student-Instance

## Output

* Public IP of EC2 instance

## Cleanup

To avoid charges:

```
terraform destroy
```

## Tools Used

* Terraform
* AWS CLI
* AWS EC2

