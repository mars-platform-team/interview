# 08. Dockerfile Improvement

**Question:** Below is a Dockerfile written in a not recommended way. Review it and list all the issues you find. Suggest improvements for production use.

```Dockerfile
FROM python:3.9
USER ROOT
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD python app.py
```

---
- What are the problems with this Dockerfile?
- How would you improve it for security, efficiency, and maintainability?

---
**End of questions.**
