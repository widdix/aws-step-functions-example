# AWS Step Functions Example

Find the blog post: https://cloudonaut.io/engaging-your-users-with-aws-step-functions/

## Installation

```
aws cloudformation create-stack --stack-name example --template-body file://template.yml --capabilities CAPABILITY_IAM
aws cloudformation wait stack-create-complete --stack-name example
```

## Clean up

```
aws cloudformation delete-stack --stack-name example
aws cloudformation wait stack-delete-complete --stack-name example
```
