# File Upload Service – Problem Statement

## Objective

Design and architect a **scalable backend service** that enables users to **upload and retrieve files**. The service should be designed with scalability, reliability, and extensibility in mind.

## Functional Requirements

- Users can **upload files** of up to **100 MB** each.
- Users can **retrieve a list of their files** at any time.
- Files may be marked as either **public or private**.
- The service should **track upload progress** so users can see how much of the file has been uploaded.
- Users must be **authenticated** before using the service.
- **Premium users** can:
    - Upload **larger files**.
    - Have **increased concurrency** or **priority** for uploads.

## Non-Functional Requirements

- The system should **support thousands of concurrent users**.
- Ensure **data integrity** and **security**.
- Enable **horizontal scalability** for future growth.
- Design for **reliability** and **fault tolerance**.
- Implement proper **monitoring**, **logging**, and **alerting** mechanisms.
- Plan for **graceful rollouts and rollbacks** during deployments.

## Constraints & Considerations

- Focus is on the **backend system design**.
- You can assume the existence of a **frontend client** (e.g., web or mobile).
- Authentication can be handled using a **third-party service** such as **Auth0**.
- The design should consider **event-driven architecture**, **asynchronous processing**, and **cloud-native practices**.
- Use **cloud storage** (e.g., S3) for storing uploaded files.

## Deliverables

- A **high-level architecture** diagram.
- Explanation of major **components and workflows**.
- Justification of **design decisions** with respect to scalability, reliability, and performance.
- Optional: Consider trade-offs and possible **enhancements** for future versions.
