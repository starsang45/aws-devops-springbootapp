Spring Boot Application Containerization Using Reusable Workflow with Caching
Course-end Project 1
Description

Objectives :


To transition a company’s application architecture from monolithic to microservice, implement DevOps CI/CD, and leverage AWS for efficient application deployments, server management, and database hosting.


Problem Statement and Motivation : 


Real-Time Scenario:


Yoda Insurance is a leading global insurance provider based in the U.S. The company offers products and services like home insurance, health insurance, car insurance, and life insurance. Currently, the company uses a monolithic application architecture, but it started facing 
difficulties in managing application deployments with the organization's growth.Seeing these challenges, the company decided to transition from its monolithic application architecture to a microservice application architecture. They also planned to implement DevOps CI/CD and other necessary automation. Yoda Insurance has chosen AWS as its primary cloud provider for servers, databases, and application deployments.


The following are the DevOps tools and their corresponding AWS services used in this project. These skills are widely used in the industry:


1. AWS CodeCommit: Tracks changes in code files for version control

2. AWS CodePipeline: Enables continuous integration and deployment

3. Docker: Deploys containerized applications
4. Docker Hub: Stores Docker images in the Docker Hub registry
5. AWS EKS: Deploys containers on the EKS Cluster


Industry Relevance


Tasks


The following tasks outline the CI/CD pipeline creation process:



Creating ECR / push code in GitHub repository to AWS code build


1. Create a code repository in GitHub to store microservice source code and push to code build

-fork the repo of the source code https://github.com/akshu20791/aws-devops-springbootapp
-create an ECR  (create private repository)
-copy authentication into github buildspec.yml 
-Back to AWS > ECR > copy the ECR images url



2. create code build project

-create connect to GitHub
-Add permission to role in IAM
-Start code build and create a project


-----------------------------------------------------------------------------------------------------------------------------------

Deploy the project 

3. Create ECS cluster
4. Create task

-create task definition
-Go to ECR > copy the image URL and paste 
-Go back to the cluster 
-Service > create
-Go to cluster created and create service

















