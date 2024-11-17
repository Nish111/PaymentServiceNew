# PaymentService

## Overview
The **PaymentService** handles secure payment processing for the eCommerce platform. It integrates with payment gateways to manage transactions, track payment statuses, and ensure reliability.

---

## Features
- Payment gateway integration (e.g., Razorpay, Stripe)
- Asynchronous communication via Kafka
- Transaction logging for audits

---

## Technologies Used
- **Java 8**
- **Spring Boot**
- **Kafka**
- **MySQL** (Database for transaction logs)

---

## Installation
1. **Database Setup**:
   Configure MySQL in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/paymentservice
   spring.datasource.username=<username>
   spring.datasource.password=<password>
