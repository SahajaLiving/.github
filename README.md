<img width="3584" height="1184" alt="Gemini_Generated_Image_kv2bmzkv2bmzkv2b" src="https://github.com/user-attachments/assets/09020cb9-5828-4973-91f1-4046230e56db" />

# Sahaja Living
### Modern Property & Tenant Management System

A full-stack ecosystem designed for boarding house & rental property owners to efficiently manage rooms, tenants, billing, payments, expenses, and maintenance workflows — all from a unified dashboard.

Sahaja Living brings automation, transparency, and a delightful user experience to daily operational management.

## System Architecture

The platform consists of multiple independent services deployed under Kubernetes for stability and scalability.

```
/admin-api        → Backend service for admin dashboard
/tenant-api       → Backend service for tenant mobile web app
/admin-web        → Web application for property owners & admins
/tenant-web       → Mobile-first web application for tenants
/docs             → Full documentation (SDLC, diagrams, API specs)
```

Each service runs independently, ensuring:
- Zero downtime during updates
- Isolated workloads (admin down ≠ tenant down)
- Improved security boundaries
- Scalable microservice structure

## Core Features

### Admin Dashboard
- Multi-property management
- Room inventory & occupancy tracking
- Tenant management
- Automated monthly billing
- Integrated payment gateway
- Expense tracking + Google Sheets import
- Maintenance workflow
- Financial dashboards & reports
- Telegram + Email notifications

### Tenant Web App (Mobile)
- Register & login
- View next bill
- Make payments
- See payment history
- View room & property info
- Submit maintenance requests
- Manage profile
- Receive notifications

## Technical Stack

### Backend
- Node.js / NestJS
- PostgreSQL
- Redis (caching & queues)
- REST API (separate admin & tenant services)
- Xendit / Midtrans payment integration
- JWT authentication

### Frontend
- Next.js / React
- TailwindCSS
- Mobile-first tenant web
- Admin dashboard with analytics

### Infrastructure
- Docker
- Kubernetes
- CI/CD via GitHub Actions
- NGINX Gateway or API Gateway
- Cloud Storage for uploads

## System Documentation

All documentation is maintained in `/docs` and includes:
- Sitemap diagrams
- Flowcharts
- Use case diagrams
- ERD (Entity Relationship Diagram)
- Functional Requirements
- Backend API Specifications
- Frontend Architecture
- Deployment Documentation

## Project Goals
- Automate manual bookkeeping and billing
- Improve communication between owner and tenants
- Reduce missed payments and unpaid bills
- Provide accurate financial insight
- Offer a scalable platform for future expansion (apps, IoT, room sensors, etc.)

## Contributing

Contributions are welcome.
Each service has its own development guidelines, branching strategy, and environment setup guide.

To contribute:
1. Fork relevant repository
2. Create a feature branch
3. Submit a pull request

## Contact
For inquiries & collaboration:
Sahaja Living Team
