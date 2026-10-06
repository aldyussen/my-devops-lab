# 🚀 DevOps Lab: SDLC + CI/CD + GitHub Actions + Docker

## Objective
Learn how to use **GitHub Actions** to automate testing and containerization for a simple Python web app.

---

## 📂 Project Structure
```
my-devops-lab/
 ┣ app/
 ┃ ┣ app.py        # Simple Flask app
 ┃ ┗ test_app.py   # Unit tests
 ┣ .github/workflows/ci.yml  # GitHub Actions pipeline
 ┣ Dockerfile       # Containerization
 ┣ requirements.txt
 ┗ README.md
```

---

## 🛠 Instructions for Students
1. **Fork this repository** to your GitHub account.  
2. Go to **Actions tab** → enable workflows.  
3. Open `app/app.py` and **change the message** (e.g., "Hello, DevOps World!" → "Hello, CI/CD!").  
4. Commit & push changes.  
5. Go to **Actions tab** and check the CI/CD pipeline run.  
6. Verify that all tests pass.  
7. (Optional) If you set DockerHub secrets in GitHub (`DOCKER_HUB_USERNAME`, `DOCKER_HUB_ACCESS_TOKEN`), the pipeline will build & push a Docker image.  

---

## ✅ Learning Outcomes
- Understand SDLC phases (requirements, coding, testing, deployment).  
- Run a CI/CD pipeline in **GitHub Actions**.  
- Build and push a Docker image automatically.  
- Experience DevOps principles: automation, feedback, collaboration.  

Good luck 🎯

## Test changes
When changing the greeting, update the expected response in `app/test_app.py` too.
Docker builds automatically. Docker Hub publishing is skipped when secrets are absent.
