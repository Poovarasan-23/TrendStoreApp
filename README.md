# TrendStoreApp
Project Summary

This project demonstrates a complete CI/CD pipeline for containerized application deployment using Kubernetes on AWS. The objective of this project is to automate the process of building, storing, deploying, and monitoring an application using modern DevOps tools.

The application source code is stored in GitHub, and whenever changes are pushed to the repository, a pipeline in Jenkins is triggered automatically. Jenkins pulls the latest code, builds a container image using Docker, and pushes the image to Docker Hub.

After the image is pushed, the pipeline deploys the application to a Kubernetes cluster running on Amazon Web Services using Amazon EKS. Kubernetes manages the application deployment using Deployment and Service configurations to ensure scalability and availability.For monitoring purposes, Grafana is used to visualize the application status and system metrics. This helps track whether the application is running properly and allows basic monitoring of the deployed environment.

This project showcases practical implementation of DevOps practices such as:
Continuous Integration
Continuous Deployment
Containerization
Cloud-based Kubernetes deployment
Application monitoring

Tools & Technologies Used:

GitHub – Source code management
Jenkins – CI/CD pipeline automation
Docker – Containerization
Docker Hub – Container image registry
Kubernetes – Container orchestration
Amazon Web Services (EKS) – Managed Kubernetes service
Grafana – Monitoring and visualization

App exposed thorugh docker image on port 3000
http://43.204.19.29:3000
App deployed on K8s LoadBalancer ARN
http://abda8564446224dfc958e9cf5ad07fac-1558734370.ap-south-1.elb.amazonaws.com
