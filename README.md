# 🏥 ConnectMedicio — Medical Association Internal Operations Portal

> A unified web and mobile operations platform built for the Medical Organization, digitizing internal workflows, reducing paperwork, and enabling members to manage their needs without physical visits to the head office.

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

---

## 📌 Overview

ConnectMedicio is a custom internal operations and member management platform developed for the **Medical Organization**. The system was built to eliminate the association's heavy reliance on physical paperwork and in-person head office visits by providing a centralized digital portal accessible via both web browser and mobile application.

The platform serves three primary user groups — **Administrators**, **Management**, and **Doctors/Members** — each with tailored interfaces and access permissions. Members can now submit requests, access documents, track application statuses, and manage their profiles entirely from their phone or desktop, significantly reducing administrative overhead at the head office.

---

## 🧩 Core Features

### 👨‍⚕️ Doctor / Member Features
- Self-service member portal — update personal and professional profiles
- Submit requests, applications, and documents digitally — no head office visit required
- Track the real-time status of submitted requests and applications
- Access association resources, circulars, and announcements
- Receive notifications for updates, approvals, and important communications
- Full-featured **mobile app** for on-the-go access

### 🏛️ Management Features
- Review and process member requests from a centralized dashboard
- Manage member records, professional registrations, and documentation
- Generate internal reports and summaries
- Broadcast announcements and circulars to members

### ⚙️ Admin Features
- Full user and role management — create, modify, and deactivate accounts
- System configuration and access control settings
- Audit logs for all critical operations
- Data export and reporting tools

---

## 🔐 Role-Based Access Control

| Role | Description |
|------|-------------|
| **Admin** | System-wide configuration, user management, audit logs |
| **Management** | Process member requests, manage records, generate reports |
| **Doctor / Member** | Self-service profile, request submission, status tracking |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Backend Framework** | Laravel (PHP) |
| **Frontend (Web)** | Blade Templates, jQuery, Bootstrap 5 |
| **Mobile Application** | React Native |
| **Database** | MySQL |
| **Authentication** | Laravel Auth with role-based guards |
| **API Layer** | RESTful API consumed by the React Native mobile app |

---

## 🏗️ Architecture

ConnectMedicio is built on a **hybrid MVC + API architecture**. The web portal uses Laravel's Blade templating for server-rendered views, while the React Native mobile application consumes a RESTful API layer built into the same Laravel backend. A unified authentication system issues separate session tokens and API tokens based on access method.

**Key design principles:**
- **Paperless workflow** — Every process that previously required physical forms or in-person visits is replicated digitally with full audit trails
- **Mobile-first member experience** — The React Native app is designed to handle 90% of member use cases without needing a desktop
- **Centralized request management** — All member submissions are funneled into a single queue for management processing, with automated status updates
- **Role-scoped data access** — Each user type sees only the data and actions relevant to their role

---

## 📸 System Modules

```
ConnectMedicio
├── Authentication (Web Sessions + Mobile API Tokens)
├── Member Portal
│   ├── Profile Management
│   ├── Request / Application Submission
│   ├── Status Tracking
│   └── Document Access
├── Management Dashboard
│   ├── Request Queue & Processing
│   ├── Member Record Management
│   └── Reporting & Exports
├── Admin Panel
│   ├── User & Role Management
│   ├── System Configuration
│   └── Audit Logs
├── Notifications & Announcements
│   ├── Push Notifications (Mobile)
│   └── Web Alerts & Circulars
└── React Native Mobile App
    ├── Member Self-Service
    ├── Request Tracking
    └── Notification Center
```

---

## 💼 Business Impact

Before ConnectMedicio, SLMA members had to physically travel to the head office in Colombo to submit applications, update records, or follow up on requests — a significant burden for doctors working across the country. The platform achieved:

- **Eliminated unnecessary office visits** — Members can complete nearly all interactions digitally
- **Reduced administrative backlog** — Centralized digital request queues replaced scattered paper piles
- **Improved transparency** — Real-time status tracking replaced phone-based follow-ups
- **Increased accessibility** — Mobile app enables access from anywhere in Sri Lanka

---

## 🚀 Key Achievements

- Designed and delivered a **full digital transformation** for SLMA's internal operations, replacing paper-driven processes with a centralized web and mobile platform serving hundreds of medical professionals
- Built a **cross-platform solution** combining a Laravel web portal and a React Native mobile app from a single shared API backend, ensuring consistent feature parity across devices
- Implemented a **role-stratified access model** enforcing strict data boundaries between Admin, Management, and Member tiers while maintaining a unified user experience
- Developed a **real-time request tracking system** allowing members to monitor submission statuses digitally, eliminating the need for in-person or phone-based follow-ups

---

> Make medical community into the digital age — one workflow at a time.
