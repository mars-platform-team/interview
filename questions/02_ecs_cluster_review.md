# 02. ECS Cluster Review

**Question:** Review the following AWS ECS cluster configuration. Identify areas for improvement in scalability, availability, and cost optimization.

```hcl
resource "aws_ecs_cluster" "main" {
  name = "my-app-cluster"
}

resource "aws_ecs_service" "web" {
  name            = "web-service"
  cluster         = aws_ecs_cluster.main.id
  task_definition = aws_ecs_task_definition.web.arn
  desired_count   = 2
}
```

---

**Next question:** [03. Automation Script Review](03_automation_script_review.md)
