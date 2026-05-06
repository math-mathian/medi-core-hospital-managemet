# MediCore — Hospital Management System
### SENG5232 Software Architecture & Design · Part 6: Implementation Prototype

**Student:** Negasi Mulualem | UGR/188566/16  
**University:** Mekelle University  
**Course:** Software Architecture and Design — 2026

---

## 🏥 About MediCore

MediCore is a mission-critical Hospital Management System (HMS) — a unified digital platform connecting every department of a modern healthcare facility.

## 🚀 Running the Prototype

Simply open `index.html` in any modern browser (Chrome, Firefox, Edge). No server or build step required.

```bash
# Option 1 — Direct open
open index.html

# Option 2 — Local server
python3 -m http.server 8080
# Then visit: http://localhost:8080
```

## 📦 Modules Demonstrated (Requirement 6)

This prototype demonstrates **interaction between 5+ modules** with working UI:

| Module | Features Shown |
|--------|---------------|
| **Dashboard** | Live stats, charts, alerts, activity feed, calendar |
| **Patient Registry** | Search, filter, register modal, EHR navigation |
| **Appointments** | Schedule, time-slot booking, queue status |
| **EHR Records** | Vitals, lab results, prescriptions, history |
| **Lab & Diagnostics** | Order queue, result upload, STAT alerts |
| **Pharmacy** | Stock levels, dispensing, prescription queue |
| **Billing** | Invoices, Chapa/Telebirr/CBHI payments |
| **Staff Management** | Doctor cards, on-duty status, ratings |
| **API Monitor** | Microservice health, live request logs |

## 🏗️ Architecture Demonstrated

- **Architectural Style:** Microservices (Node.js services on ports 3001–3005)
- **Frontend:** React.js-style component UI (HTML/CSS/JS prototype)
- **Backend:** Node.js + Express + RabbitMQ + Redis
- **Database:** PostgreSQL + MongoDB + AWS S3
- **DevOps:** Docker + Kubernetes (AWS EKS) + GitHub Actions

## ✅ Fulfills ASR Quality Attributes

- **Availability:** 99.97% uptime shown in API monitor
- **Performance:** Sub-50ms API response times displayed
- **Security:** Role-based access, allergy alerts (Penicillin warning)
- **Scalability:** Multiple service instances shown (2–3 per service)
- **Usability:** Intuitive navigation across 10 modules
- **Maintainability:** Microservices architecture with circuit breaker pattern

## 📁 File Structure

```
medicore-prototype/
└── index.html          # Complete single-file prototype (102KB)
```

---
*MediCore Prototype — SENG5232 Part 6 · Mekelle University 2026*
