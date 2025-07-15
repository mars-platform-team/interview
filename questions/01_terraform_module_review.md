"""
Question: Review the following Terraform module code. Suggest improvements for reusability, security, and maintainability.
"""

# Example Terraform module (Python pseudo-code for interview context)
module "s3_bucket" {
  source = "terraform-aws-modules/s3-bucket/aws"
  bucket = "my-app-bucket"
  acl    = "private"
  versioning = {
    enabled = true
  }
  tags = {
    Environment = "dev"
    Owner       = "team"
  }
}
