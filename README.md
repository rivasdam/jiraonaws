# Jira on AWS
Customized Quick Start for deploying Jira on AWS


This CloudFormation templates are based on quickstart: https://aws.amazon.com/quickstart/architecture/jira/. The main difference is that the former requires you to deploy a previous template for ASI (Atlassian Standard Infrastructure) and is heavily tied to the outputs it generates.

This template instead is intended to deploy the quickstart without needing to create ASI and leveraging existing VPC structure with public and private subnets. You also will maintain them on your own S3 bucket instead of the quickstart's original one.

DISCLAIMER: These CloudFormation templates are intended for testing purposes only and the sample code is provided "AS-IS". For production use, it is recommended to validate and update the code accordingly to your AWS environment.




