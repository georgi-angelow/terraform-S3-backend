# S3 backend for Terraform

Createe a s3 bucket and dynamodb table to use as terraform backend.

* dynamodb_table_name = terraform-lock
* s3_bucket_name = <account_id>-terraform-states

```html
├── main.tf
├── outputs.tf
├── README.md
└── variables.tf
```

# usage

```
1. Changes variables in variables.tf
2. You need to have profile setuped in ~/.aws/credentials
3. terraform init
4. terraform plan

# apply the change
5. terraform apply
```
