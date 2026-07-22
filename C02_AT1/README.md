# SecureVote Cloud Campus Polling Platform With Audit Logs and Result Integrity

## Capstone Title

**SecureVote Cloud Campus Polling Platform With Audit Logs and Result Integrity**

---

## Project Overview

SecureVote is a cloud-based web application developed for conducting secure campus elections. The system enables students to cast votes online while ensuring authentication, audit logging, and result integrity. It is designed for a single college with approximately 10,000 registered students and uses Firebase cloud services for secure and scalable deployment.

**Technology Stack**
- HTML
- CSS
- JavaScript
- Firebase Authentication
- Cloud Firestore
- Firebase Hosting
- Firebase Storage

---

# Infrastructure Sizing Summary

| Component | Configuration |
|-----------|---------------|
| Deployment Type | Cloud-based Web Application |
| Expected Users | 10,000 Students |
| Active Users (Election Day) | 60% |
| Workload Type | API-Based & Database-Heavy |
| CPU | 4 vCPU |
| RAM | 8 GB |
| Storage | 50 GB SSD |
| Database | Cloud Firestore |
| Authentication | Firebase Authentication |
| File Storage | Firebase Storage |
| Hosting | Firebase Hosting |
| Virtualization | Cloud-Managed Virtualization |

---

# Final Recommendation

The SecureVote platform is recommended to use a cloud-native architecture with Firebase services for hosting, authentication, database, and file storage. Based on the workload estimation, a configuration of **4 vCPU, 8 GB RAM, and 50 GB SSD** is suitable for the prototype deployment. Cloud-managed virtualization provides scalability, reliability, and simplified infrastructure management. Snapshots should be taken before major deployments and system updates, while clones should be used for testing and demonstration environments. This infrastructure offers a secure, scalable, and cost-effective foundation for conducting campus elections while ensuring audit logging and result integrity.

---

**Course:** CSA15 – Cloud Computing and Big Data Analytics

**Assessment:** CO2 AT1 – Capstone Infrastructure Sizing

**Student:** *Your Name*

**Register Number:** *Your Register Number*
