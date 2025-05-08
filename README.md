# Secure Multi-Tier Web Application on AWS

This project demonstrates a secure deployment of a 3-tier web application architecture on AWS. It includes:

- **Frontend** hosted on S3 + CloudFront
- **Backend** running a Python Flask app on EC2
- **Database** using Amazon RDS with encryption
- **Security Stack**:
  - IAM roles and policies
  - VPC with public/private subnets
  - AWS WAF, GuardDuty, Security Hub, Inspector
  - AWS KMS encryption for data at rest
  - AWS Config and CloudTrail for monitoring

## Folder Structure

