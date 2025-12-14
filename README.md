# ecsDeployment
Deployed a Dockerized React LMS frontend on AWS ECS Fargate using ECR and an Application Load Balancer. Implemented secure networking, IAM roles, and documented real-world troubleshooting for health check failures and container resource constraints.

This project documents how I containerized and deployed a Learning Management System (LMS) frontend using **Docker** and **AWS ECS (Fargate)**. The goal wasn’t just to get the app running, but to understand how containers behave in a real cloud environment — including what happens when things break and how to fix them.

I took a React-based LMS frontend, packaged it into a Docker container, pushed it to Amazon ECR, and deployed it on ECS Fargate behind an Application Load Balancer. Along the way, I intentionally introduced common misconfigurations to practice troubleshooting and recovery.

This project focuses on:
- Building and running Docker containers locally
- Deploying containers to AWS using ECS Fargate
- Configuring networking, security groups, and IAM roles
- Debugging real ECS issues like failed health checks and resource limits
