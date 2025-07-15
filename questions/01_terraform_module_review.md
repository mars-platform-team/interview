# 01. Terraform Module Review

**Question:** Review the following Terraform module code. Suggest improvements for reusability, security, and maintainability.

```hcl
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
```

---

**Next question:** [02. ECS Cluster Review](02_ecs_cluster_review.md)
