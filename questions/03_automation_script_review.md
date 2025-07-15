"""
Question: Review the following Bash and Python automation scripts. Suggest improvements for reliability, error handling, and maintainability.
"""

# Bash script example
#!/bin/bash
aws s3 cp /data/backup s3://my-app-backup

# Python script example
import os
os.system('aws logs describe-log-groups')
