# 04. Boto3 EC2 Start Instance Review

**Question:** Below is a Python function that starts an EC2 instance using Boto3. Review the code and suggest improvements or identify any bugs related to error handling, permissions, and network reliability.

```python
import boto3

def start_instance(instance_id):
    ec2 = boto3.client('ec2')
    ec2.start_instances(InstanceIds=[instance_id])
    print('Instance started')
```

---
- What improvements would you make to this function?
- Are there any bugs or missing error handling?
- How would you make this code more robust for production use?

**Next question:** [05. Dockerfile Review](05_dockerfile_review.md)
