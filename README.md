# Jenkins CI/CD Learning Project

A comprehensive Jenkins learning project demonstrating Continuous Integration and Continuous Delivery pipelines for two sample applications: **FoodHub** and **ShopEase**.

## 📋 Project Overview

This project contains hands-on examples of setting up Jenkins pipelines, configuring webhooks, and automating build processes. It serves as both a learning resource and practical demonstration of Jenkins best practices.

## 📁 Project Structure

```
Jenkins_task/
├── README.md                          # Project documentation
├── Jenkins_Exam.pdf                   # Jenkins concepts & exam questions
└── ScreenShots/                       # Visual documentation
    ├── foodhub-1.png                 # FoodHub initial setup
    ├── foodhub-jenkins.png           # FoodHub Jenkins configuration
    ├── foodhub-webhook-1.png         # FoodHub webhook setup
    ├── Foodhub_updated_wh.png        # FoodHub updated webhook
    ├── Jenkins-Build-ShopEase.png    # ShopEase build output
    ├── ShopEase-1st.png              # ShopEase initial setup
    ├── ShopEase_updated_wh.png       # ShopEase updated webhook
    └── Webhook-shopease.png          # ShopEase webhook configuration
```

## 🎯 Key Projects

### 1. **FoodHub**
- E-commerce application for food delivery
- Integrated with Jenkins CI/CD pipeline
- Automated build triggers via GitHub webhooks

### 2. **ShopEase**
- E-commerce platform for shopping
- Complete Jenkins pipeline setup
- Webhook-based automatic builds

## 🔧 Jenkins Concepts Covered

| Concept | Description |
|---------|-------------|
| **Continuous Integration** | Automated testing and building on code changes |
| **Continuous Delivery** | Automated pipeline stages to prepare for release |
| **Pipeline Project** | Code-based job definition using Jenkinsfile |
| **Webhooks** | Automatic build triggers on Git push events |
| **Git Plugin** | Integration with GitHub repositories |
| **Jenkins Agents** | Distributed execution nodes for builds |
| **Shell Commands** | Using `sh` command in Pipeline scripts |
| **SSH Credentials** | Secure SSH agent usage in pipelines |

## 📚 Jenkins Exam Questions & Answers

Essential Jenkins concepts covered in the learning materials:

| # | Question | Answer |
|---|----------|--------|
| 1 | What is Jenkins mainly used for? | **B)** Continuous Integration and Continuous Delivery |
| 2 | Which type of job allows you to define build steps using code in Jenkins? | **B)** Pipeline Project |
| 3 | Which file is used to define a pipeline in Jenkins? | **C)** Jenkinsfile |
| 4 | What is the purpose of a Jenkins Agent (Node)? | **B)** To execute jobs assigned by the Jenkins controller |
| 5 | Which plugin is required to connect Jenkins with GitHub? | **B)** Git Plugin |
| 6 | What is the purpose of a Webhook in Jenkins CI/CD? | **B)** To trigger build automatically on code push |
| 7 | Which command is used inside Jenkins Pipeline to execute shell commands? | **C)** sh |
| 8 | What is the purpose of post block in Jenkins Pipeline? | **B)** Execute steps after pipeline stages |
| 9 | What is the use of sshagent in Jenkins Pipeline? | **C)** Use stored SSH credentials during execution |
| 10 | What happens if a stage fails in Jenkins Pipeline (by default)? | **B)** The pipeline stops execution |

## 📸 Screenshots & Documentation

Visual guides are provided in the `ScreenShots/` directory showing:
- Initial application setup for FoodHub and ShopEase
- Jenkins job configuration steps
- Webhook integration and configuration
- Build execution results
- Updated webhook configurations

## 🚀 Getting Started

1. **Review Fundamentals** - Study the Jenkins exam questions for core concepts
2. **Visual Learning** - Check the screenshot examples for FoodHub and ShopEase setups
3. **Understand Automation** - Explore how GitHub webhooks trigger automatic Jenkins builds
4. **Study Pipelines** - Examine the Jenkinsfile patterns and configuration

## 💡 Best Practices Demonstrated

- ✅ Infrastructure as Code (Jenkinsfile approach)
- ✅ Automated CI/CD pipelines
- ✅ Webhook-based automation
- ✅ Secure credential management with SSH agents
- ✅ Multi-stage pipeline execution
- ✅ Distributed Jenkins agent architecture

## 📖 Reference Material

- **Jenkins_Exam.pdf** - Complete exam guide with all questions and explanations
- **ScreenShots/** - Step-by-step visual configuration guides
- **FoodHub & ShopEase Examples** - Real-world pipeline implementation patterns

---

**Last Updated:** June 2026  
**Type:** Jenkins Learning & Practice Project  
**Difficulty Level:** Intermediate


