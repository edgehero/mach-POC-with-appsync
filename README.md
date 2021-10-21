mach-POC-with-appsync

make sure terraform and machcomposer are installed
https://docs.machcomposer.io/

1. manually create a S3 bucket in AWS and add this to the terraform_config in the main.yml
2. change the accountid in the terraform_config to the right AWS account
3. after that create a user in AWS IAM the admin rights to S3.

to deploy to aws:
run in console

```
export AWS_ACCESS_KEY_ID=xxx
export AWS_SECRET_ACCESS_KEY=xxx
export AWS_DEFAULT_REGION=eu-west-1
mach apply
```
