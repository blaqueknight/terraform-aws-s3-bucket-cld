# AWS S3 Bucket Module

A simple Terraform module for creating an S3 bucket.

## Usage

```hcl
module "s3_bucket" {
  source = "app.terraform.io/policy-as-code-training-corey/terraform-aws-s3-bucket-cld/aws"
  version = "v1.0.0"
  bucket_name = "corey-bucket-20260611"
}
```

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|----------|
| bucket_name | Name of the S3 bucket | string | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| bucket_id | The name of the bucket |
| bucket_arn | The ARN of the bucket |
