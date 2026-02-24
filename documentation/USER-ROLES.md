# 👥 User Roles & Permissions

## Role Overview

### 1. **Patient** 👤
- **Platform:** Mobile App
- **Access:** Sign Up, Login, View Profile
- **Can Do:**
  - Create account
  - Login with email/username
  - Reset password
  - Verify email

### 2. **Center Admin** 🏥
- **Platform:** Admin Dashboard (Web)
- **Access:** Sign Up, Login, Manage Center
- **Can Do:**
  - Create admin account
  - Login with email/username
  - Reset password
  - Verify email
  - (Future) Manage patients & staff

### 3. **Superadmin** 👑
- **Platform:** Superadmin Dashboard (Web)
- **Access:** Sign Up, Login, Manage All Accounts
- **Can Do:**
  - Create superadmin account
  - Login with email/username
  - Reset password
  - Verify email
  - (Future) Manage multiple centers
  - (Future) Create admin accounts

### 4. **Donor** 💳
- **Platform:** Donation Platform (Web)
- **Access:** Sign Up, Login, Browse Campaigns
- **Can Do:**
  - Create donor account
  - Login with email/username
  - Reset password
  - Verify email
  - (Future) Make donations

---

## Authentication Rules

### Sign Up Requirements
- Email (valid format)
- Password (min 6 characters)
- Username (min 3 characters, unique)
- Full name

### Login Requirements
- Email OR Username
- Password

### Email Verification
- OTP code sent to email
- Code valid for 24 hours
- Account locked until verified (optional)

---

## Access Control Matrix

| Role | Mobile App | Admin Dashboard | Superadmin Dashboard | Donation Platform |
|------|-----------|-----------------|--------------------|--------------------|
| Patient | ✅ | ❌ | ❌ | ✅ Optional |
| Center Admin | ❌ | ✅ | ❌ | ❌ |
| Superadmin | ❌ | ❌ | ✅ | ✅ View |
| Donor | ❌ | ❌ | ❌ | ✅ |

---

**Last Updated:** February 9, 2026  
**Status:** Active