## Required Secrets:

To add the following GHA secrets, navigate to your GitHub repository > `Settings` > `Secrets and variables` > `Actions` > `New repository secret` for each secret you need to add, filling in the name and value fields.

- AWS_ACCESS_KEY_ID: Your AWS access key ID for the IAM user
- AWS_SECRET_ACCESS_KEY: Your AWS secret access key
- AWS_REGION: The AWS region where your ECR repository is located (e.g., us-east-1).
- ECR_REPOSITORY: The name of your Amazon ECR repository (e.g., my-repo).
- AWS_ACCOUNT_ID: Your AWS account ID (a 12-digit number).
