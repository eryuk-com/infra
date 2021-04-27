# Ian-Terraform

## IAM
global IAM(not module)
### Folder
```
.\global
|-- global\
|  |-- base.tf
|  |-- every-policy.tf
|  |-- iam.tf
|  |-- output.tf
|  |-- variable.tf
```
### Usage
```
$ terraform init
$ terraform output encrypted_aws_iam_secrets
```

## VPC