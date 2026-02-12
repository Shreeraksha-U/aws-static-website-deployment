# aws-static-website-deployment
# AWS Static Website Deployment (DevOps Fundamentals)

## Overview
This project demonstrates the deployment of a static website on AWS using
EC2 and S3 with secure IAM-based access control. The objective was to gain
hands-on experience with cloud services, Linux administration, and basic
DevOps practices.

## Tech Stack & Services
- Amazon EC2 (Red Hat Linux)
- Amazon S3
- AWS IAM (users & groups)
- Linux (RHEL commands)
- MobaXterm (SSH access)

## Architecture
User accesses a static website hosted on an EC2 instance.
The website files are stored and managed using Amazon S3.
Access to AWS resources is controlled using IAM groups and policies.

## Implementation Steps
1. Launched an EC2 instance using Red Hat Linux
2. Connected securely using SSH via MobaXterm
3. Created an S3 bucket and uploaded `index.html`
4. Configured IAM users and groups with least-privilege access
5. Verified website deployment and access

## Security Practices Followed
- Root account was not used
- IAM users and groups were configured
- Sensitive credentials were never exposed
- Public access was limited to required services only

## What I Learned
- Basics of AWS cloud infrastructure
- Linux server navigation and file management
- Importance of IAM and access control
- How real-world deployments differ from theory

## Future Improvements
- Automate infrastructure using Terraform
- Add CI/CD pipeline using GitHub Actions
- Use CloudFront for CDN
- Enable monitoring with CloudWatch


