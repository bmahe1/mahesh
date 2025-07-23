# Frontend CI/CD - Static Website with AWS S3 + SonarCloud

This repository contains the frontend login page for the Mahesh project. It is deployed using AWS CodePipeline and S3, with quality scanning through SonarCloud.

## 🛠 Tech Stack
- HTML/CSS
- SonarCloud (JavaScript/HTML scanning)
- AWS CodeBuild
- AWS CodePipeline
- Amazon S3 (Static Website Hosting)

## 🚀 Deployment Flow
1. Code pushed to GitHub
2. CodePipeline triggers CodeBuild
3. CodeBuild runs SonarCloud scan
4. Build artifacts deployed to S3

## 🔐 Secrets
- `SONAR_TOKEN` stored in AWS Secrets Manager

## 📄 Files
- `index.html`: Login form (with demo credentials visible)
- `buildspec.yml`: Build instructions for CodeBuild
- `sonar-project.properties`: SonarCloud configuration

## 🧪 SonarCloud Setup
- Project Key: `frontend-project`
- Organization: your-org-name
