# Serverless Personal To-do List Application

## Overview

This project demonstrates a fully **serverless personal task management application** built on **Amazon Web Services (AWS)**. Using AWS Lambda, API Gateway, DynamoDB, and AWS SAM, the application supports full CRUD (Create, Read, Update, Delete) functionality for to-do items via a RESTful API.

---

## Features

- Serverless architecture (no server management)
- CRUD operations on to-do items
- RESTful API endpoints
- Scalable and cost-effective design
- Infrastructure as Code using AWS SAM
- NoSQL storage using DynamoDB
- Deployed via Pulumi and AWS CLI

---

## Architecture

- **AWS Lambda** – Backend logic for handling CRUD operations.
- **API Gateway** – Exposes RESTful endpoints to users.
- **DynamoDB** – Stores to-do items in a fast, scalable NoSQL format.
- **AWS SAM** – Defines and deploys the application infrastructure.
- **Pulumi** – Manages infrastructure provisioning and environment configs.

---

## Tech Stack

- **Programming Language:** Node.js (Lambda backend)
- **Cloud Provider:** AWS
- **Infrastructure Management:** AWS SAM, Pulumi
- **Database:** Amazon DynamoDB
- **API Management:** Amazon API Gateway
- **Testing Tools:** Postman, AWS CloudWatch

---

## Getting Started

### Prerequisites

- AWS CLI configured with your IAM credentials
- AWS SAM CLI
- Pulumi CLI
- Node.js (v18+)
