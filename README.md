# 🛒 Django Store Project

A production-ready Django-based backend service for managing an e-commerce platform, complete with OpenID Connect authentication, nested product categories, SMS and email notifications, RESTful API, testing, CI/CD, and Kubernetes deployment.

---

## 📌 Features

- 🔐 OpenID Connect authentication (OIDC)
- 🧾 Customer, Category (with arbitrary-depth nesting), Product, and Order models
- 🌐 REST API for product management, pricing, and order processing
- 📩 SMS notifications to customers via [Africa's Talking](https://africastalking.com/)
- 📧 Email notifications to administrators on order placement
- ✅ Unit tests with coverage and optional E2E tests
- 🔄 CI/CD pipeline (GitHub Actions)
- ☸️ Kubernetes deployment ready (Minikube/Kind supported)
- 📃 Auto-generated API documentation with Swagger (drf-yasg)

---

## 🧱 Tech Stack

- **Backend**: Python, Django, Django REST Framework
- **Auth**: OpenID Connect (e.g., Keycloak, Auth0)
- **Notifications**: Africa's Talking (SMS), SMTP (email)
- **API Docs**: Swagger via `drf-yasg`
- **CI/CD**: GitHub Actions
- **Deployment**: Docker, Kubernetes (Minikube or Kind)
- **Database**: PostgreSQL (default) or SQLite (dev)

---

## 🚀 Getting Started

### 1. Clone the Project

```bash
git clone https://github.com/Michieka/django-store.git
cd django-store
