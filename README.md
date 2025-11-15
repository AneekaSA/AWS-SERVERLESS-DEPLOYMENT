# Student Manager – Serverless Web Application
## Serverless
### S3 | CloudFront | API Gateway | Lambda | DynamoDB | IAM

<img width="1916" height="1011" alt="Screenshot 2025-11-15 121028" src="https://github.com/user-attachments/assets/9808df82-4dcc-4101-b33c-6023791b0adf" />
<img width="1916" height="854" alt="Screenshot 2025-11-15 121051" src="https://github.com/user-attachments/assets/d48e08c5-3077-4ea7-acdd-913805e1bff5" />


## Project Overview

Student Manager is a fully serverless web application built using AWS cloud-native services. The project focuses on delivering a lightweight, scalable, and cost-efficient application without managing any servers. The frontend is hosted on S3 and delivered globally using CloudFront, while backend logic is executed through AWS Lambda functions exposed via API Gateway. DynamoDB serves as the persistent data store for student records.

The application supports two core functionalities:
- Fetching the current list of students
- Adding new student records

Both operations are handled using separate Lambda functions, ensuring clean separation of logic and easy maintainability.

Key Serverless practices implemented:

- Static frontend hosting using Amazon **S3**
- Global caching and acceleration via **CloudFront CDN**
- API orchestration with **API Gateway**
- Fully serverless backend logic using **Lambda**
- Data storage using **DynamoDB**
- Secure resource access via **IAM Roles & Policies**
- Event-driven, autoscaling, zero-maintenance architecture
- Clear separation of frontend/UI and backend/API layers
- Use of environment variables for configuration management

This project demonstrates the ability to build an end-to-end serverless application using AWS-native services, showcasing API design, Lambda-based compute, S3 hosting, cloud security, and scalable data handling with DynamoDB. It also highlights how serverless systems reduce operational overhead, provide instant scalability, and enable pay-per-use efficiency for modern cloud applications.

---
