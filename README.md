# 👋 Hi, I'm Jeyaprakash

### ☁️ AWS Cloud DevOps Engineer | Automation | CI/CD | Infrastructure as Code

I am a **Cloud DevOps Engineer** focused on building, automating, and maintaining scalable and reliable cloud infrastructure using **AWS, Terraform, Docker, Kubernetes, Jenkins, and modern DevOps practices**.

I have a strong background in **software testing and quality assurance** and am transitioning my experience toward **Cloud & DevOps engineering**, with hands-on practice in AWS infrastructure, CI/CD pipelines, automation, monitoring, security, and disaster recovery.

---

## 🚀 About Me

* ☁️ Working toward a career as an **AWS Cloud DevOps Engineer**
* 🔧 Hands-on experience with AWS infrastructure and networking
* 🏗️ Building infrastructure using **Terraform**
* 🔄 Creating CI/CD pipelines using **Jenkins**
* 🐳 Working with **Docker & Kubernetes**
* 📦 Practicing Infrastructure as Code and automation
* 🔐 Learning DevSecOps practices with **SonarQube & Trivy**
* 📊 Monitoring and observability using **CloudWatch, Prometheus & Grafana**
* 🚨 Working with centralized logging using **Splunk, Loki & Fluent Bit**
* 🔀 Practicing GitOps using **Argo CD**
* 🌎 Designing AWS **Multi-Region Disaster Recovery** architectures
* 📚 Continuously improving my AWS Cloud & DevOps skills

---

# 🛠️ Technical Skills

## ☁️ AWS

* EC2
* VPC
* IAM
* S3
* EBS
* EFS
* RDS
* DynamoDB
* Lambda
* ECS
* ECR
* ALB
* Auto Scaling
* Route 53
* CloudFront
* CloudWatch
* CloudTrail
* SQS
* SNS
* EventBridge
* KMS
* VPC Endpoints
* NAT Gateway
* Transit Gateway
* AWS Backup
* Disaster Recovery

---

## 🔧 DevOps Tools

| Category                 | Tools                           |
| ------------------------ | ------------------------------- |
| Version Control          | Git, GitHub                     |
| CI/CD                    | Jenkins                         |
| Infrastructure as Code   | Terraform, CloudFormation       |
| Configuration Management | Ansible                         |
| Containers               | Docker                          |
| Container Orchestration  | Kubernetes                      |
| Package Management       | Helm                            |
| GitOps                   | Argo CD                         |
| Code Quality             | SonarQube                       |
| Security Scanning        | Trivy                           |
| Monitoring               | Prometheus, Grafana, CloudWatch |
| Logging                  | Splunk, Loki, Fluent Bit        |
| Operating Systems        | Linux, Ubuntu                   |
| Scripting                | Bash, Python                    |
| Cloud                    | Amazon Web Services             |

---

# 🏗️ AWS Architecture & DevOps Practice

I have been practicing real-world AWS infrastructure scenarios including:

### 🔹 3-Tier Architecture

```text
                    Internet
                       │
                       ▼
                 Route 53 / DNS
                       │
                       ▼
                 Application Load
                    Balancer
                       │
              ┌────────┴────────┐
              ▼                 ▼
        Public Subnet      Public Subnet
              │                 │
             EC2               EC2
              │                 │
              └────────┬────────┘
                       │
                       ▼
                Private Subnet
                       │
                       ▼
                    RDS DB
```

### 🔹 High Availability

* Multi-AZ architecture
* Application Load Balancer
* Auto Scaling Groups
* Launch Templates
* Private/Public Subnets
* NAT Gateway
* Route Tables
* Internet Gateway

---

# 🌎 Disaster Recovery

Currently practicing **AWS Multi-Region Disaster Recovery** using a **Pilot Light strategy**.

### Architecture concepts practiced:

* Multi-Region VPC
* Transit Gateway
* Transit Gateway Inter-Region Peering
* Amazon EFS
* EFS Mount Targets
* S3 Cross-Region Replication
* S3 Lifecycle Management
* VPC Endpoints
* EC2
* Route 53
* RPO / RTO planning

### DR Target

```text
Primary Region                         DR Region
──────────────                         ─────────

     VPC A                                VPC B
       │                                    │
      TGW  ═══ Inter-Region Peering ═══   TGW
       │                                    │
      EC2                                  EC2
       │                                    │
      EFS                                  EFS
       │                                    │
      S3  ═════ Cross Region Replication ═ S3
```

**Target RPO:** 30 minutes
**Target RTO:** 30 minutes

---

# 🔄 CI/CD Pipeline

Working toward implementing complete DevOps pipelines such as:

```text
Developer
    │
    ▼
  GitHub
    │
    ▼
  Jenkins
    │
    ├── Build
    │
    ├── Unit Test
    │
    ├── SonarQube
    │
    ├── Trivy Security Scan
    │
    ├── Docker Build
    │
    ▼
   ECR
    │
    ▼
 Kubernetes / ECS
    │
    ▼
 Production
```

---

# 📦 Infrastructure as Code

Using **Terraform** to automate AWS infrastructure.

Example Terraform workflow:

```text
Terraform Code
      │
      ▼
terraform init
      │
      ▼
terraform validate
      │
      ▼
terraform plan
      │
      ▼
terraform apply
      │
      ▼
AWS Infrastructure
```

Practicing:

* Variables
* Outputs
* Modules
* `count`
* `for_each`
* `terraform.tfvars`
* Provider configuration
* Remote State
* State management
* Lifecycle rules
* `create_before_destroy`
* `ignore_changes`

---

# 🐳 Containerization

Working with:

* Docker Images
* Dockerfiles
* Docker Containers
* Docker Hub
* Amazon ECR
* Kubernetes
* Deployments
* Services
* ConfigMaps
* Secrets
* Helm Charts

---

# 📊 Monitoring & Logging

### Monitoring

```text
Application
     │
     ▼
Prometheus
     │
     ▼
Grafana
```

### Logging

```text
Application
     │
     ▼
Fluent Bit
     │
     ├── Loki
     │
     └── Splunk
```

Also practicing **AWS CloudWatch** for:

* Metrics
* Logs
* Alarms
* Dashboards
* EC2 monitoring
* Application monitoring

---

# 🔐 DevSecOps

Security practices I am learning and implementing:

* IAM least privilege
* Security Groups
* Network ACLs
* KMS encryption
* Secrets management
* SonarQube code analysis
* Trivy vulnerability scanning
* Container image security
* Infrastructure security

---

# 📂 Featured Projects

### ☁️ AWS 3-Tier Architecture

AWS infrastructure with:

* VPC
* Public & Private Subnets
* ALB
* EC2
* Auto Scaling
* RDS
* NAT Gateway
* Internet Gateway
* Route Tables

### 🌎 Multi-Region AWS Disaster Recovery

Pilot Light DR architecture using:

* Multi-Region VPC
* Transit Gateway
* TGW Peering
* EFS
* S3 Replication
* EC2
* Route 53
* RPO/RTO planning

### 🔄 AWS S3 Event-Driven Architecture

Practicing:

```text
S3 Upload
    │
    ▼
Event Notification / EventBridge
    │
    ▼
Lambda
    │
    ▼
SQS / SNS
```

### 🏗️ Terraform AWS Infrastructure

Infrastructure provisioning using reusable Terraform configurations for AWS services.

---

# 📈 Currently Learning

```text
AWS Cloud
   ↓
Terraform
   ↓
Jenkins
   ↓
Docker
   ↓
Kubernetes
   ↓
Helm
   ↓
Prometheus + Grafana
   ↓
DevSecOps
   ↓
Argo CD / GitOps
```

---

# 🎯 Career Goal

My goal is to become a strong **AWS Cloud DevOps Engineer** capable of designing, automating, deploying, monitoring, and troubleshooting production-grade cloud infrastructure.

I am particularly interested in:

* ☁️ Cloud Infrastructure
* ⚙️ DevOps Automation
* 🔄 CI/CD
* 🏗️ Infrastructure as Code
* 🐳 Containerization
* ☸️ Kubernetes
* 🔐 DevSecOps
* 📊 Observability
* 🌎 Cloud Disaster Recovery

---

## ⭐ Thanks for Visiting!

I'm continuously learning and building hands-on AWS & DevOps projects.

**Learn → Practice → Automate → Deploy → Monitor → Improve 🚀**
