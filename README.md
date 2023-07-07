# aws-secrets-github-actions

How to use AWS Secrets Manager

1. Create a Secret inside AWS Secrets Manager
2. Enter in your AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY into the Github Actions secrets feature
3. Use the following actions inside Github Actions to use your secrets

   a. configure-aws-credentials
   
   b. aws-secretsmanager-get-secret

5. When we get our AWS secrets, assign them to a variable and use inside Github Actions
