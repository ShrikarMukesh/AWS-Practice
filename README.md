---

# **AWS Practice – Services Explained**

---

## **1) IAM – Identity & Access Management**

**Purpose:** Authentication and authorization in AWS.

**Key concepts**

* Users, Groups, Roles
* Policies (JSON-based permissions)
* Least privilege principle

**Real use**

* EC2 role to access S3 (no access keys needed)
* CI/CD pipeline role for deployments

---

## **2) S3 – Simple Storage Service**

**Purpose:** Object storage (highly durable and scalable).

**Key concepts**

* Buckets, Objects
* Versioning
* Lifecycle rules
* Encryption (SSE-S3, SSE-KMS)

**Real use**

* Store logs, backups, static website files
* Data lake storage

---

## **3) EC2 – Elastic Compute Cloud**

**Purpose:** Virtual servers in the cloud.

**Key concepts**

* AMI, Instance types
* Security Groups
* Key pairs
* Elastic IP

**Real use**

* Host Spring Boot applications
* Run batch jobs or custom services

---

## **4) ECS – Elastic Container Service**

**Purpose:** Container orchestration (AWS-managed).

**Key concepts**

* Task Definition
* Cluster
* Service
* Launch types: EC2 / Fargate

**Real use**

* Run Dockerized microservices without managing Kubernetes

---

## **5) ECR – Elastic Container Registry**

**Purpose:** Private Docker image repository.

**Key concepts**

* Image repositories
* Lifecycle policies
* IAM-based access

**Real use**

* Store images used by ECS / EKS
* Secure alternative to Docker Hub

---

## **6) EBS & EFS**

### **EBS – Elastic Block Store**

* Block storage for EC2
* Tied to a single AZ
* Used like a disk

### **EFS – Elastic File System**

* Shared file system
* Multi-AZ
* POSIX compatible

**Real use**

* EBS: Database storage
* EFS: Shared storage across multiple EC2 instances

---

## **7) RDS – Relational Database Service**

**Purpose:** Managed relational databases.

**Supported engines**

* MySQL, PostgreSQL, Oracle, SQL Server, MariaDB, Aurora

**Key features**

* Automated backups
* Read replicas
* Multi-AZ

**Real use**

* Transactional databases for applications

---

## **8) VPC – Virtual Private Cloud**

**Purpose:** Network isolation and control.

**Key concepts**

* Subnets (public/private)
* Route tables
* Internet Gateway
* NAT Gateway

**Real use**

* Deploy applications securely inside private subnets

---

## **9) VPC2 (Advanced VPC / Networking Concepts)**

Typically refers to:

* VPC Peering
* Transit Gateway
* PrivateLink
* Hybrid networking (VPN / Direct Connect)

**Real use**

* Connect multiple VPCs across accounts
* On-prem to AWS connectivity

---

## **10) Route 53**

**Purpose:** DNS and traffic routing.

**Key features**

* Domain registration
* Health checks
* Routing policies (Latency, Failover, Weighted)

**Real use**

* Route traffic to Load Balancers or EC2
* Blue/Green deployments

---

## **11) Auto Scaling**

**Purpose:** Automatically adjust compute capacity.

**Types**

* EC2 Auto Scaling
* Application Auto Scaling
* Target tracking / step scaling

**Real use**

* Scale EC2 based on CPU or requests
* Cost optimization + high availability

---

## **12) CloudWatch**

**Purpose:** Monitoring and observability.

**Key features**

* Metrics
* Logs
* Alarms
* Dashboards

**Real use**

* Monitor CPU, memory, API latency
* Trigger alarms and scaling actions

---

## **13) Application Integration**

**Services**

* SQS (Simple Queue Service)
* SNS (Simple Notification Service)
* EventBridge
* Step Functions

**Real use**

* Asynchronous communication
* Event-driven microservices
* Workflow orchestration

---

## **15) Analytics**

**Services**

* Athena
* Redshift
* Glue
* Kinesis

**Real use**

* Query S3 data using SQL
* Streaming analytics
* ETL pipelines

---

## **16) Machine Learning**

**Services**

* SageMaker
* Rekognition
* Comprehend
* Lex

**Real use**

* Build/train ML models
* Image and text analysis
* Chatbots

---

## **17) Security**

**Services**

* KMS (Key Management Service)
* Secrets Manager
* Shield
* WAF
* GuardDuty

**Real use**

* Encrypt data
* Secure secrets
* Protect applications from attacks

---

## **18) Serverless**

**Services**

* Lambda
* API Gateway
* DynamoDB
* Step Functions

**Real use**

* Event-driven processing
* No server management
* Pay per execution

---

## **19) Containers**

**Services**

* ECS
* EKS (Managed Kubernetes)
* ECR
* Fargate

**Real use**

* Microservices architecture
* Containerized Spring Boot applications

---

