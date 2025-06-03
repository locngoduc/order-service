# Order Service 🛒

![Java](https://img.shields.io/badge/Java-17-orange?logo=java) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2-brightgreen?logo=spring) ![AWS](https://img.shields.io/badge/AWS-Learning-yellow?logo=amazonaws) ![Practice](https://img.shields.io/badge/Practice-Project-blue)

This repository contains the **application code** for an **Ordering System**, built as a practice project to deepen my understanding of **AWS cloud services**. It’s written in **Java**, showcasing a scalable backend for order management, integrated with AWS resources.

## 🚀 Project Purpose
This project is part of a hands-on learning journey to master **AWS** and cloud-native development. The `order-service` handles the core business logic for creating, retrieving, and managing orders, interacting seamlessly with AWS infrastructure defined in the `order-infra` repository.

## 🛠️ Tech Stack
- **Programming Language**: Java 21 ☕
- **Framework**: Spring Boot 3.2 🌱
- **Build Tool**: Maven 📦
- **Database Access**: AWS SDK for Java (DynamoDB integration) 📊
- **Testing**: JUnit 5 🧪
- **Other Libraries**:
  - Lombok (for cleaner code) ✂️
  - Jackson (for JSON serialization) 📝

## 🌐 AWS Resources (Consumed)
- **DynamoDB**: Stores order data with high scalability 📈
- **Lambda**: Executes order processing logic ⚡
- **API Gateway**: Exposes REST endpoints for order operations 🌍

## 📂 Repository Structure
```
order-service/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/orderservice/
│   │   │       ├── controller/  # REST controllers
│   │   │       ├── service/     # Business logic
│   │   │       ├── repository/  # DynamoDB access
│   │   │       └── model/       # Order entities
│   │   └── resources/
│   │       └── application.yml  # Spring Boot config
│   └── test/
│       └── java/                # Unit tests
├── pom.xml                      # Maven dependencies
└── README.md
```

## 🏁 Getting Started
1. **Clone the repository**:
   ```bash
   git clone https://github.com/locngoduc/order-service.git
   ```
2. **Install dependencies**:
   ```bash
   mvn install
   ```
3. **Run locally** (requires AWS credentials configured):
   ```bash
   mvn spring-boot:run
   ```
   - Ensure `order-infra` is deployed to provision AWS resources.

## 🔗 Related Repositories
- **Infrastructure**: [order-infra](https://github.com/locngoduc/order-infra.git) (AWS CDK setup)
- **Orchestrator**: [order-orchestrator](https://github.com/locngoduc/order-orchestrator.git) (Deployment coordination)

## 📚 Learning Goals
- Master AWS SDK for Java to interact with DynamoDB.
- Build RESTful APIs with Spring Boot for AWS Lambda.
- Practice clean code principles with Java.

## 💡 Why This Impresses
- **AWS Integration**: Seamlessly connects with DynamoDB and Lambda for a cloud-native architecture.
- **Java Best Practices**: Uses modern Java features and Spring Boot for a robust backend.
- **Scalability**: Designed to handle order processing at scale with AWS.

---

*Built with 💻 and ☁️ as a learning project for AWS mastery.*
