# 🛠️ MY AWS Cloud Services

This document outlines the plan to build a set of AWS-like services from scratch. Each service includes a summary, key features, and estimated build time. This will serve as a reference and progress tracker.

---

## ✅ Services To Build

1. EC2 Clone (Compute Instances)
2. S3 Clone (Object Storage)
3. Secrets Manager / Parameter Store
4. SNS (Notification System)
5. SQS (Message Queue)
6. CloudWatch Logs Clone (Logging System)
7. Route 53 Clone (DNS Manager)
8. ECR Clone (Docker Registry)
9. IAM Clone (Users, API Keys, Permissions)
10. CodeDeploy / CodePipeline (CI/CD)
11. Admin Dashboard UI

---

## 1. 🖥️ EC2 Clone (Compute Instances)

- **Description**: Create, manage, and access virtual machines on demand.
- **Key Features**:
  - VM provisioning and control (start/stop/reboot/delete)
  - SSH key injection and networking
  - Snapshots and resizing
  - React-based UI for instance management
- **Estimated Time**: 10–14 days

---

## 2. 🗂️ S3 Clone (Object Storage)

- **Description**: Store and retrieve files in buckets with public/private access control.
- **Key Features**:
  - Bucket and object creation
  - File upload/download/delete
  - Signed URLs for temporary access
  - Public/private toggle for objects
- **Estimated Time**: 1–2 days

---

## 3. 🔐 Secrets Manager / Parameter Store

- **Description**: Encrypted storage for secrets, tokens, config values.
- **Key Features**:
  - Key-value storage
  - Encryption at rest
  - Access control per secret
- **Estimated Time**: 1 day

---

## 4. 📣 SNS (Notification System)

- **Description**: Topic-based pub/sub system to push messages to subscribers.
- **Key Features**:
  - Topic creation and subscription
  - Webhook and email delivery
  - Message logging
- **Estimated Time**: 1 day

---

## 5. 📨 SQS (Message Queue)

- **Description**: FIFO and standard message queue system for async tasks.
- **Key Features**:
  - Queue creation and deletion
  - Push/pop messages
  - Visibility timeout and retries
- **Estimated Time**: 2 days

---

## 6. 📄 CloudWatch Logs

- **Description**: Centralized log collector with filtering and search.
- **Key Features**:
  - Log ingestion from services
  - Search and filter logs by service/date
  - Retention policies
- **Estimated Time**: 2 days

---

## 7. 🌐 Route 53 (DNS Manager)

- **Description**: Manage DNS records for your domains.
- **Key Features**:
  - Zone and record creation
  - A, AAAA, CNAME, TXT record types
  - TTL and propagation control
- **Estimated Time**: 1 day

---

## 8. 🐳 ECR Clone (Docker Registry)

- **Description**: Private Docker image hosting.
- **Key Features**:
  - Push/pull Docker images
  - Tag management
  - Authentication and access control
- **Estimated Time**: 2–3 days

---

## 9. 👤 IAM Clone

- **Description**: Manage users, API keys, roles and permissions.
- **Key Features**:
  - User signup/login
  - Role-based or permission-based access
  - API key management
- **Estimated Time**: 2–3 days

---

## 10. 🚀 CodeDeploy / CodePipeline

- **Description**: Automate Git-based deployments.
- **Key Features**:
  - Git hook integration
  - Build + deploy pipelines
  - Rollbacks and logs
- **Estimated Time**: 2–4 days

---

## 11. 🧑‍💻 Admin Dashboard UI

- **Description**: Frontend to control and visualize all services.
- **Key Features**:
  - React-based UI
  - Service status overview
  - CRUD interfaces for each service
- **Estimated Time**: 5–7 days

---

## 📅 Total Estimated Time

- **Total (in days)**: ~29 to 40 days
- **Total (in weeks)**: ~6 to 8 weeks
- **Total (in months)**: ~1.5 to 2 months

