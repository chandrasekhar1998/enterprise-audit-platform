# Enterprise Audit Management Platform

A production-oriented Enterprise Audit Management Platform built with
Python, Django REST Framework, PostgreSQL, FastAPI, Angular, Redis,
Celery, RabbitMQ, Docker and modern DevOps/observability tools.

The project is designed to demonstrate real-world backend and full-stack
engineering practices including REST API development, microservices,
database optimization, asynchronous processing, caching, testing,
CI/CD, monitoring and production debugging.

---

## 🚧 Project Status

**Current Status:** Under Active Development

The project is being developed incrementally, starting with the Django
Audit Service and gradually introducing PostgreSQL, Docker,
microservices, caching, asynchronous processing, CI/CD and monitoring.

### Implemented So Far

- Repository initialized
- Django Audit Service initialized
- Django REST Framework configured
- Poetry dependency management
- PostgreSQL driver configured
- Environment configuration support
- Pytest development dependency
- Ruff development dependency
- Coverage development dependency
- Basic Django application structure

### Planned

- PostgreSQL integration
- Audit management APIs
- Authentication and authorization
- Role-Based Access Control (RBAC)
- FastAPI microservices
- Redis caching
- Celery background processing
- RabbitMQ messaging
- Angular frontend
- Docker and Docker Compose
- Nginx reverse proxy
- Automated testing
- GitHub Actions CI/CD
- Prometheus metrics
- Grafana dashboards
- Sentry error monitoring
- Production logging
- Load testing
- Production debugging scenarios

---

# 🎯 Project Objective

The goal of this project is to build a realistic enterprise-grade
application rather than a simple CRUD application.

The platform will support the complete audit lifecycle:

```text
Create Audit
     ↓
Assign Auditor
     ↓
Audit Checklist
     ↓
Collect Evidence
     ↓
Record Observations
     ↓
Review
     ↓
Approval / Rejection
     ↓
Audit Completion
     ↓
Reporting