# 05. Dockerfile Review

**Question:** Below is a sample Dockerfile. Review it and suggest improvements for security, efficiency, and maintainability. Identify any bugs or bad practices.

```Dockerfile
FROM python:3.9
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
```

---
- What improvements would you make to this Dockerfile?
- Are there any security or efficiency issues?
- How would you optimize this for production use?

**Next question:** [06. Dockerfile Improvement](08_dockerfile_improvement.md)
