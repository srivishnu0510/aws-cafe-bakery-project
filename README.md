# ☁️ AWS Cafe & Bakery Project

This project demonstrates how to host a simple web application on AWS using the Well-Architected Framework.

## 🧱 Architecture
- VPC with public/private subnets
- EC2 (Flask App)
- Application Load Balancer
- RDS (MySQL)
- S3 (App code storage)
- CloudFormation (Automation)
- CloudWatch (Monitoring)

## 🚀 Deployment Steps
1. Uploaded app.zip to S3
2. Deployed infrastructure using CloudFormation (`vpc-cafe-bakery.yaml`)
3. Connected EC2 → RDS
4. Verified app via ALB DNS name

## 📸 Screenshots
![Architecture Diagram](screenshots/architecture.png)
![Website Output](screenshots/website.png)

## 🎯 Outcome
A fully automated and monitored 3-tier web app hosted on AWS.
