# 🏗️ System Design Study

A growing collection of backend system design problems and their detailed solutions. Each problem includes a problem statement, architectural diagram, technical breakdown, and considerations for scalability, reliability, and deployment.

This repo is built for demonstrating system design principles and practices, focusing on backend systems. It is intented to be used for practice and learning.

---

## 🧠 Problem Index

### 1. Scalable File Upload Service

**Description:**  
Design a backend system to support authenticated users uploading and retrieving files up to 100 MB. The system supports tracking upload progress, public/private file access, and premium-tier benefits like higher upload limits and concurrency.

**Highlights:**
- Pre-signed S3 URLs
- Kafka-based async processing
- WebSocket feedback loop
- Auth0 authentication
- Caching and DLQ strategies

📁 [Problem 1](problem_1/Problem.md) | [Solution](problem_1/Solution.md)

---

More problems coming soon!
