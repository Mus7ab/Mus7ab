# Hi, I'm Musaab 👋

### AWS Cloud Engineer | DevOps Engineer

I build **secure, scalable, and automated AWS infrastructure** using Infrastructure as Code, containers, Kubernetes, and CI/CD.

My work focuses on turning cloud architecture into **repeatable, maintainable, and observable environments** using AWS, Terraform, Docker, Kubernetes, GitHub Actions, and Linux.

With a background in Full-Stack Development (MERN), I also understand the application side of the systems I deploy and automate.

---

## ☁️ What I Build

* 🏗️ AWS cloud infrastructure with clear network and security boundaries
* 🔐 IAM and least-privilege access controls
* ⚙️ Terraform-managed and repeatable infrastructure
* 🐳 Containerized microservices on AWS ECS Fargate
* ☸️ Kubernetes workloads on Amazon EKS
* 🔄 CI/CD pipelines with GitHub Actions
* ⚡ Event-driven and serverless AWS architectures
* 📊 Monitoring and observability with CloudWatch, Prometheus, Grafana, and X-Ray

---

## 🧩 Engineering Capabilities

### 🔐 Security

* IAM roles and scoped permissions
* Security-group-based access control
* Private RDS database deployments
* SSM Session Manager for keyless EC2 administration
* IAM Roles for Service Accounts (IRSA)
* Least-privilege network paths

### 🛡️ Reliability

* Multi-AZ VPC and compute architectures
* Application Load Balancing
* EC2 Auto Scaling
* Health-checked traffic routing
* Kubernetes health and scaling mechanisms
* SQS Dead Letter Queues for failure isolation

### ⚙️ Automation

* Terraform Infrastructure as Code
* Reusable Terraform modules
* Remote Terraform state
* GitHub Actions CI/CD
* Automated Terraform plan/apply workflows
* Helm-based Kubernetes deployments

### 📊 Observability

* Amazon CloudWatch
* Prometheus
* Grafana
* AWS X-Ray

---

# 🚀 Featured Projects

## 1. Production-Style 3-Tier AWS Web Application

A production-style 3-tier AWS architecture with a **public ALB, EC2 Auto Scaling web tier, and private PostgreSQL RDS database**, provisioned with Terraform and deployed through GitHub Actions.

### Architecture & Engineering

* VPC spanning 2 Availability Zones
* Public and private subnet structure
* Application Load Balancer
* EC2 Auto Scaling Group with a minimum of 2 instances
* Private Single-AZ PostgreSQL RDS
* Security-group chaining: ALB → EC2 → RDS
* SSM Session Manager instead of SSH
* Remote Terraform state in Amazon S3
* GitHub Actions Terraform plan/apply workflow

**Stack:** AWS • Terraform • VPC • ALB • EC2 • Auto Scaling • RDS • S3 • IAM • SSM • GitHub Actions

> **Design note:** RDS is intentionally Single-AZ for this portfolio project. Multi-AZ RDS would be the appropriate next step for a production workload requiring database high availability.

🔗 **[Repository](https://github.com/Mus7ab/three-tier-webapp)**

---

## 2. Containerized Microservices Platform

A containerized **Orders + Users microservices platform** deployed to AWS ECS Fargate with Application Load Balancer path-based routing.

### Architecture & Engineering

* Independent Orders and Users services
* Dockerized workloads
* Amazon ECS Fargate
* Application Load Balancer
* Path-based routing
* Multi-AZ ECS deployment
* Amazon ECR container images
* Terraform infrastructure
* GitHub Actions CI/CD

**Stack:** AWS • ECS Fargate • Docker • ECR • ALB • Terraform • GitHub Actions • Node.js

🔗 **[Repository](https://github.com/Mus7ab/microservices-orders-users)**

---

## 3. Kubernetes Microservices on Amazon EKS

A production-style Kubernetes environment for deploying and monitoring containerized microservices on Amazon EKS.

### Architecture & Engineering

* Amazon EKS
* Kubernetes workloads
* Helm charts
* NGINX Ingress
* AWS Network Load Balancer
* IAM Roles for Service Accounts (IRSA)
* Prometheus monitoring
* Grafana dashboards
* Kubernetes autoscaling
* GitHub Actions deployment automation

**Stack:** AWS EKS • Kubernetes • Helm • Docker • NGINX Ingress • NLB • IRSA • Prometheus • Grafana • GitHub Actions

🔗 **[Repository](https://github.com/Mus7ab/eks-kubernetes-microservices)**

---

## 4. Multi-Environment Infrastructure as Code

Production-inspired AWS infrastructure demonstrating **repeatable Terraform deployments across Development, Staging, and Production environments**.

### Architecture & Engineering

* Reusable Terraform modules
* Environment isolation
* Isolated remote state
* Environment-specific configuration
* IAM controls
* Resource tagging
* GitHub Actions CI/CD
* Approval-gated promotion between environments

**Stack:** AWS • Terraform • GitHub Actions • IAM • S3 • Infrastructure as Code

🔗 **[Repository](https://github.com/Mus7ab/terraform-multi-env-iac)**

---

## 5. Serverless Event-Driven Order Platform

An event-driven serverless architecture demonstrating **decoupled communication, asynchronous processing, failure isolation, and observability**.

### Architecture

```text
API Gateway
     ↓
  Lambda
     ↓
 DynamoDB
     ↓
EventBridge
     ↓
   SNS
 ┌───┼────────┐
 ↓   ↓        ↓
SQS SQS      SQS
 ↓   ↓        ↓
Email Warehouse Inventory
```

### Engineering

* API Gateway
* AWS Lambda
* DynamoDB
* EventBridge
* SNS fan-out
* Multiple SQS consumers
* Dead Letter Queues
* CloudWatch monitoring
* AWS X-Ray tracing
* Modular Terraform Infrastructure as Code
* Tested SNS fan-out and message delivery

**Stack:** AWS • Terraform • API Gateway • Lambda • DynamoDB • EventBridge • SNS • SQS • CloudWatch • X-Ray

🔗 **[Repository](https://github.com/Mus7ab/serverless-order-platform)**

---

## 6. AWS Static Website Hosting

A static website hosted using **Amazon S3**, demonstrating S3 website hosting, bucket policies, IAM access, and basic cloud security.

### Architecture & Engineering

* Amazon S3 static website hosting
* S3 bucket policy
* IAM-based administration
* Public website endpoint
* HTML/CSS deployment

**Stack:** AWS S3 • IAM • HTML • CSS

> **Planned improvements:** CloudFront, HTTPS with ACM, Route 53 custom domain, GitHub Actions deployment, and Terraform-based infrastructure.

🔗 **[Repository](https://github.com/Mus7ab/aws-static-website-hosting)**

---

# 🛠️ Core Technologies

### AWS & Cloud

AWS IAM • VPC • EC2 • S3 • RDS • Route 53 • CloudFront • ALB • Auto Scaling • ECS Fargate • EKS • Lambda • API Gateway • DynamoDB • EventBridge • SNS • SQS • CloudWatch • X-Ray

### Infrastructure & DevOps

Terraform • Infrastructure as Code • Docker • Kubernetes • Helm • GitHub Actions • CI/CD • Automated Deployments

### Monitoring & Observability

Prometheus • Grafana • CloudWatch • X-Ray

### Linux & Networking

Linux • SSH • SSM • Nginx • DNS • TCP/IP • Networking Fundamentals • Process Management • System Services • Troubleshooting

### Development Background

JavaScript • React.js • Node.js • Express.js • MongoDB • REST APIs

---

# 📈 Engineering Progression

My portfolio demonstrates a progression from foundational AWS services to complete cloud architectures:

**AWS Static Website Hosting**
↓
**3-Tier AWS Infrastructure**
↓
**Containerized Microservices on ECS Fargate**
↓
**Kubernetes on Amazon EKS**
↓
**Multi-Environment Terraform Infrastructure**
↓
**Event-Driven Serverless Architecture**

The goal is to demonstrate not only knowledge of individual technologies, but how they work together to build **secure, automated, scalable, and reliable cloud systems**.

---

# 🎯 Current Focus

Currently deepening my expertise in:

* Kubernetes and Amazon EKS
* AWS security and IAM
* Infrastructure automation with Terraform
* CI/CD and deployment automation
* Cloud observability and troubleshooting
* Reliability and high-availability architecture
* Multi-environment AWS infrastructure

---

# 💼 Open to Opportunities

I'm interested in **AWS Cloud Engineer, Cloud Engineer, and DevOps Engineer opportunities** where I can contribute to cloud infrastructure, automation, CI/CD, containerization, and reliable AWS systems.

---

# 🤝 Connect With Me

* 💼 **LinkedIn:** [linkedin.com/in/musaabmohamedan1](https://www.linkedin.com/in/musaabmohamedan1)
* 📧 **Email:** [musaab.cloud@gmail.com](mailto:musaab.cloud@gmail.com)
