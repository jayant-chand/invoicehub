InvoiceHub – SaaS Billing & Subscription Platform

InvoiceHub is a production-ready SaaS billing and subscription management platform built using Django REST Framework and React.
The project is designed to demonstrate real-world backend architecture, secure authentication, background processing, and containerised deployment.

This application focuses on scalability, security, and clean system design, similar to what modern SaaS products use in production.

🚀 Features
🔐 Authentication & Authorization

JWT-based authentication

Role-based access control (Admin / User)

Secure API access using Django REST Framework

💳 SaaS Billing & Subscriptions

Subscription plans and billing workflows

Payment processing logic (Stripe integration ready)

Invoice generation and billing history

🗄️ Backend Architecture

Django + Django REST Framework

PostgreSQL for persistent data storage

Redis for caching and background task coordination

Celery for asynchronous job processing

🐳 DevOps & Infrastructure

Fully containerised using Docker and Docker Compose

Environment-based configuration (development / production)

Designed for deployment behind NGINX and Gunicorn

🌐 Frontend

React-based frontend

Secure API integration and development

Dashboard-style UI for users and admins

🏗️ Tech Stack

Backend

Python

Django

Django REST Framework

PostgreSQL

Redis

Celery

Frontend

React

JavaScript

DevOps

Docker

Docker Compose


📐 System Architecture
Client (Browser)
   ↓
React Frontend
   ↓
Django REST API (Gunicorn)
   ↓
PostgreSQL  ←→  Redis
   ↓
Celery Workers


⚙️ Running the Project Locally
Prerequisites

Docker

Docker Compose

Steps
git clone https://github.com/jayant-chand/invoicehub.git
cd invoicehub
docker-compose up --build


Backend: http://localhost:8000

Frontend: http://localhost:3000



📌 Project Goals

This project was built to:

Understand and implement real SaaS backend architecture

Work with JWT authentication and role-based access

Design scalable REST APIs

Use background processing for non-blocking tasks

Practice containerised deployments


🔮 Future Enhancements

Google & GitHub OAuth authentication

CI/CD pipeline using GitHub Actions

Deployment to AWS (EC2, S3, HTTPS)

NGINX reverse proxy with SSL

API rate limiting and audit logging



👤 Author

Jayant Chand
Software Developer
GitHub: https://github.com/jayant-chand