# Build a CI/CD Pipeline for the 2048 Game using AWS CodePipeline, ECS, and ECR

### Overview of Project ☁️
This project focuses on setting up a CI/CD pipeline for deploying a Dockerized version of the 2048 game to AWS. The pipeline automates the process of building, testing, and deploying the game to a scalable infrastructure using Amazon ECS, Amazon ECR, and AWS CodePipeline.

### Key tasks include:
* Building and pushing a Docker image of the 2048 game to Amazon ECR.
* Setting up a CodePipeline to automate the build and deploy process.
* Deploying the Dockerized game to Amazon ECS using a Fargate launch type.
* In this video, you'll learn how to integrate various AWS services to create a streamlined CI/CD workflow, reducing manual intervention and enabling faster, reliable application deployment.

### Steps to be performed
We'll go through the following steps in the next few lessons.
1. Set Up ECS Cluster and ECR Repository
2. Prepare the 2048 Game Code
3. Set Up CodeBuild for Continuous Integration
4. Set Up CodePipeline for Continuous Deployment

### Services Used 🛠
1. AWS CodePipeline: Orchestrates the CI/CD pipeline, automating the build, test, and deployment stages. [Automation]
2. Amazon ECS Deploys and manages containerized applications using Fargate for serverless container management. [Deployment]
3. Amazon ECR: Stores and manages Docker images used in the ECS tasks. [Container Registry] 
4. AWS CodeBuild: Handles the build phase of the pipeline, including Docker image creation.[Build]
5. IAM Roles & Policies: Ensure secure access between the services involved. [Permissions]

### Estimated Time & Cost ⚙️
* This project is estimated to take about 2-3 hours
* Cost: ~$1 or less, assuming minimal usage of AWS Fargate, ECR, and CodeBuild.

### Architecture Diagram:
<img width="1357" height="540" alt="image" src="https://github.com/user-attachments/assets/e83df0dc-4cbf-443f-a9c3-a8e5c70ce94a" />

### Final Result
This is what our project will look like, once built:
<img width="1832" height="1012" alt="image" src="https://github.com/user-attachments/assets/6c9ea41e-18e3-4fc6-8b2a-3599645461f3" />

