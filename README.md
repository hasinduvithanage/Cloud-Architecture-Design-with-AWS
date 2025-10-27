# Cloud-Architecture-Design-with-AWS

## COS10034 Cloud Computing

## 📌 Project Overview
This repository contains the **Serverless/Event-driven Architectural Design Report** for **Assignment 3** of the COS10034 Cloud Computing unit at Swinburne University of Technology.  

The project explores the design and justification of a **scalable, secure, and cost-efficient cloud architecture** using AWS services. It focuses on meeting the needs of a growing media-based business scenario while ensuring performance, reliability, and extensibility.

---

## 🏗️ Architecture Highlights
- **Amazon Route 53** – Domain Name System (DNS) routing.  
- **AWS WAF & AWS Shield** – Web security and DDoS protection.  
- **Amazon Cognito + IAM** – Secure authentication and access management.  
- **Amazon CloudFront** – Global content delivery (CDN).  
- **Amazon VPC + EC2 + Auto Scaling + Elastic Load Balancer** – Scalable, fault-tolerant compute layer.  
- **Amazon S3** – Primary media storage.  
- **AWS Lambda** – Serverless backend functions for event-driven processing.  
- **AWS Elastic Transcoder** – Media transcoding (formats, thumbnails).  
- **AWS Rekognition** – AI-driven image and video analysis.  
- **Amazon DynamoDB + ElastiCache** – Scalable NoSQL storage and caching.  
- **Amazon SQS** – Message queuing for decoupled architecture.  
- **CloudWatch + CloudTrail** – Monitoring, logging, auditing.  
- **AWS Backup** – Centralized backup and disaster recovery.

---

## 📊 Design Criteria
- **Performance & Scalability**: Auto Scaling & Lambda enable rapid response to demand surges.  
- **Reliability**: Decoupled components with SQS, multi-AZ deployments, and durable S3 storage.  
- **Security**: Cognito, IAM, WAF, and Shield provide multi-layered security.  
- **Cost Efficiency**: Pay-as-you-go services, serverless design, and managed databases reduce overhead.  

Estimated costs were calculated using the **AWS Pricing Calculator**, with annual costs projected at **$162,016.92** (including upfront setup).

---

## 📐 UML Diagrams
- **Collaboration Diagrams**: Uploading & Downloading workflows.  
- **Sequence Diagrams**: Event-driven processes triggered by uploads and downloads.  

---

## 🔎 Key Comparisons
- **VMs vs Containers vs Serverless**: Justification for serverless as the most cost-efficient and scalable.  
- **SQL vs NoSQL**: Rationale for DynamoDB (NoSQL) for high throughput and flexibility.  
- **Push vs Pull Messaging**: SQS chosen for controlled, reliable task processing.  
- **Tiered Architectures**: Discussion of 2-tier vs 3-tier with preference for 3-tier modularity.  

---

## ✅ Conclusion
This design fulfills all requirements by providing a **secure, scalable, cost-effective, and extensible AWS architecture**. It supports current media storage/transcoding needs while enabling future AI-powered features like automated tagging and content moderation.

---

## 🙏 Acknowledgments
Special thanks to:
- **Tharindu Suraj** (Swinburne University) for academic guidance.  
- **Amazon Web Services (AWS)** for providing tools, documentation, and pricing calculators.  

---

## 📚 References
- [AWS Pricing Calculator](https://calculator.aws/#/addService)  
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/)  
- [AWS Web Hosting Best Practices Whitepaper](https://d1.awsstatic.com/whitepapers/aws-web-hosting-best-practices.pdf)  
- [NoSQL vs SQL Databases – MongoDB](https://www.mongodb.com/nosql-explained/nosql-vs-sql)  
- [Types of Load Balancers – Solve The Network](https://blog.solvethenetwork.com/different-type-of-load-balancers/)  
- [AWS Web Application Hosting Whitepapers](https://docs.aws.amazon.com/whitepapers/latest/web-application-hosting-best-practices/)  

---

## 👥 Authors
- Hasindu Sathsara Vithanage  
