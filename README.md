# Terraform AWS S3 Static Website

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)

A static website deployed on AWS S3 using Terraform (Infrastructure as Code).

## Features
- ✅ Automated S3 bucket creation
- ✅ Static website hosting enabled
- ✅ Public read access via bucket policy
- ✅ Zero-downtime deployments

## How It Works
1. Terraform provisions an S3 bucket with website hosting enabled  
2. Uploads an `index.html` file  
3. Outputs the website URL  

## Usage
```bash
terraform init
terraform apply
