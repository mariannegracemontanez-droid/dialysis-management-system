# 🏥 Dialysis Management System

A comprehensive mobile and web platform for managing dialysis patient care, appointments, medical records, and donations.

## 📱 Project Components

### 1. **Mobile App (Flutter)** - Patient Interface
A cross-platform mobile application for dialysis patients.

**Features:**
- Patient registration & authentication
- Appointment scheduling & rescheduling
- Dialysis session history & tracking
- Medical records management
- Donation tracking
- Profile management
- Notifications & alerts

**Location:** `/mobile-app`

---

### 2. **Admin Dashboard (Web)** - Center Management
Web-based management portal for dialysis centers.

**Features:**
- Patient management & monitoring
- Staff/Employee management
- Appointment scheduling system
- Dialysis session records
- Equipment management
- Reports & analytics
- Center configuration

**Location:** `/web-admin-dashboard`

---

### 3. **Donation Platform (Web)** - Public Donations
Public website for donating to support dialysis patients.

**Features:**
- Campaign browsing & details
- Donor registration & authentication
- Secure donation processing
- Payment integration
- Donation history & receipts
- Impact tracking

**Location:** `/web-donation-platform`

---

### 4. **Backend (Firebase)** - Core Services
Cloud-based backend services powering all platforms.

**Services:**
- User authentication & authorization
- Realtime database for patient records
- Cloud Functions for business logic
- Cloud Storage for documents
- Security rules & data protection

**Location:** `/backend-firebase`

---

## 🛠️ Technology Stack

| Component | Technology |
|-----------|-----------|
| **Mobile App** | Flutter 3.x, Dart |
| **Web Platforms** | React/Vue.js, TypeScript |
| **Backend** | Firebase (Auth, Realtime DB, Cloud Functions) |
| **Database** | Firebase Realtime Database + Firestore |
| **Storage** | Firebase Cloud Storage |
| **Hosting** | Firebase Hosting |
| **IDE** | Visual Studio Code |
| **Version Control** | Git & GitHub |
| **Design** | Figma |

---

## ✨ Key Features

### 📱 Mobile App (Patient)
- ✅ User authentication (Email/Password)
- ✅ Email verification (OTP)
- ✅ Appointment booking & rescheduling
- ✅ Dialysis session history
- ✅ Medical records & documents viewing
- ✅ Donation tracking
- ✅ Profile management
- ✅ Password management
- ✅ Login history
- ✅ Privacy & security settings
- ✅ Push notifications

### 🖥️ Admin Dashboard
- ✅ Patient management
- ✅ Appointment management
- ✅ Staff/Employee management
- ✅ Medical records management
- ✅ Equipment tracking
- ✅ Analytics & reports
- ✅ Center configuration
- ✅ User role management

### 💳 Donation Platform
- ✅ Campaign management
- ✅ Donor registration
- ✅ Donation processing
- ✅ Payment integration
- ✅ Donation history
- ✅ Impact tracking

---

## 👥 User Roles

1. **Patient** - Mobile app user, books appointments, views records
2. **Nurse/Technician** - Staff, manages dialysis sessions
3. **Doctor** - Staff, reviews medical records
4. **Center Admin** - Manages center operations
5. **Superadmin** - Manages all centers
6. **Donor** - Web platform, makes donations

---

## 📋 Prerequisites

Before starting, ensure you have:
- ✅ GitHub account
- ✅ Firebase account (free tier)
- ✅ Git installed on your computer
- ✅ Flutter SDK (for mobile development)
- ✅ Visual Studio Code
- ✅ Node.js & npm (for backend)
- ✅ ~5 GB free disk space

---

## 🚀 Getting Started

### 1. Clone Repository
```bash
git clone https://github.com/mariannegracemontanez-droid/dialysis-management-system.git
cd dialysis-management-system
```

### 2. Navigate by Component
- **Mobile App:** See `/mobile-app/README.md`
- **Admin Dashboard:** See `/web-admin-dashboard/README.md`
- **Donation Platform:** See `/web-donation-platform/README.md`
- **Backend:** See `/backend-firebase/README.md`

### 3. Setup Instructions
- Complete setup guides: See `/documentation/setup/`
- Database design: See `/documentation/database/`
- API documentation: See `/documentation/api/`

---

## 📁 Project Structure

```
dialysis-management-system/
├── 📱 mobile-app/                    # Flutter mobile app
├── 🖥️ web-admin-dashboard/           # Admin dashboard
├── 💳 web-donation-platform/         # Donation website
├── ⚙️ backend-firebase/              # Firebase backend
├── 📄 database-schemas/              # Database designs
├── 🎨 designs/                       # Figma prototypes
├── 📚 documentation/                 # Complete docs
├── .gitignore                        # Git ignore rules
├── README.md                         # This file
├── LICENSE                           # Apache License 2.0
└── PROJECT-PLAN.md                   # Detailed plan
```

---

## 📚 Documentation

- [Features List](./documentation/FEATURES.md)
- [User Roles & Permissions](./documentation/USER-ROLES.md)
- [System Architecture](./documentation/ARCHITECTURE.md)
- [Database Design](./documentation/DATABASE-DESIGN.md)
- [API Endpoints](./documentation/api/API-ENDPOINTS.md)
- [Screen Documentation](./documentation/SCREENS-DOCUMENTATION.md)
- [Project Timeline](./documentation/PROJECT-TIMELINE.md)
- [Testing Strategy](./documentation/TESTING-STRATEGY.md)

---

## 🔒 Security & Privacy

This project will handle real patient data (dialysis medical information).

**Security Features:**
- ✅ User authentication with Firebase Auth
- ✅ Role-based access control (RBAC)
- ✅ Data encryption (at rest & in transit)
- ✅ Secure password hashing
- ✅ Session management
- ✅ Audit logging

**Data Protection:**
- ✅ HIPAA compliance (for production)
- ✅ Privacy policy (in development)
- ✅ Data retention policies
- ✅ Secure backups

**Testing Phase:** Dummy data only  
**Development/Production:** Real patient data with full compliance

---

## 🎨 Design & Prototypes

Figma Prototype: [Add link to your Figma file]

All design assets: `/designs/`

---

## 👥 Team Information

**Project Name:** Dialysis Management System  
**Project Type:** Capstone Project  
**Target Users:** Dialysis patients, medical staff, donors  
**Institution:** [Your School Name]

### Team Members
- [Your Name] - [Your Role]
- [Team Member 2] - [Role]
- [Team Member 3] - [Role]

---

## 📝 License

This project is licensed under the **Apache License 2.0** - see [LICENSE](./LICENSE) file for details.

### Why Apache 2.0?
- ✅ Includes patent protection (important for healthcare)
- ✅ Clear liability disclaimers
- ✅ Allows commercial use & modifications
- ✅ Professional standard for medical apps

### Important Note
This is an educational capstone project. For production use with real patient data, additional security measures and legal compliance are required.

---

## 🔗 Useful Links

- [Firebase Console](https://console.firebase.google.com)
- [Flutter Documentation](https://flutter.dev)
- [GitHub Repository](https://github.com/mariannegracemontanez-droid/dialysis-management-system)

---

## 📞 Support & Contact

For questions or issues:
- Create a GitHub issue
- Contact the development team
- Email: [your-email@example.com]

---

## 📊 Project Status

```
Phase 1: Project Structure & Planning     ✅ IN PROGRESS
Phase 2: Development Environment Setup    ⏳ Pending
Phase 3: Backend Development              ⏳ Pending
Phase 4: Mobile App Development           ⏳ Pending
Phase 5: Web Dashboard Development        ⏳ Pending
Phase 6: Testing & Deployment             ⏳ Pending
```

---

**Project Start Date:** February 9, 2026  
**Last Updated:** February 9, 2026  
**Version:** 1.0.0 (Planning Phase)