# Cloudformation Tutorial

## Deploy

```
aws cloudformation deploy --stack-name ireton-ec2 --template-file ./ec2-instance.yaml
```

## Show Me the Whatif

```
aws cloudformation deploy --stack-name ireton-ec2 --template-file ./ec2-instance.yaml --no-execute-changeset
```
