# Jira on AWS
Customized Quick Start for deploying Jira on AWS

These CloudFormation templates are based on quickstart: https://aws.amazon.com/quickstart/architecture/jira/. The main difference is that the former requires you to deploy a previous template for ASI (Atlassian Standard Infrastructure) and is heavily tied to the outputs it generates.

This template instead is intended to deploy the quickstart without needing to create ASI and leveraging existing VPC structure with public and private subnets. You also will maintain them on your own S3 bucket instead of the quickstart's original one.

Instructions:
1. Create a S3 Bucket. Make the Bucket with Public Access.
2. Create a folder named: "quickstart-atlassian-jira". Open the folder and create a subfolder called "templates".
3. Upload the content on this repo inside templates folder. Make sure the content is publicly available.
4. Copy the URL of quickstart-jira-dc.template-mod.yaml (click on the checkbox next to the filename and click on Copy URL button)
5. Create a new Stack in CloudFormation using the URL copied previously.
6. Complete the required parameters and run the stack. 

DISCLAIMER: These CloudFormation templates are intended for testing purposes only and the sample code is provided "AS-IS". For production use, it is recommended to validate and update the code accordingly to your AWS environment.




