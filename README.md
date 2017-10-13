# AWS Step Functions Example

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
