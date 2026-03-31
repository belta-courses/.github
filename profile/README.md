# BeltaCourses | Udemy like platform

## 📌 Summary
A scalable full-stack courses platform inspired by Udemy, enabling instructors to publish courses, students to purchase them, and instructors to receive payouts. The system is built with role-based access control, secure authentication, and a modular architecture designed for extensibility and performance.

---

## 🌐 Live Preview

- **Client Website:** client-courses.imbeltagy.com

- **Admin Panel:** admin-courses.imbeltagy.com

---

## 📦 Repositories

- **API:** https://github.com/belta-courses/backend

- **Client Website:** https://github.com/belta-courses/client

- **Admin Panel:** https://github.com/belta-courses/admin

---

## 🚀 Deployment

- **Deployed on:** Custom VPS (Virtual Private Server)

---

## ⚙️ Features

- 🔐 **Authentication**
  - Email-only login
  - Secure session handling

- 👥 **Role-Based Access Control**
  - Roles: Admin, Moderator, Instructor, Student
  - Moderators have configurable permissions
  - Permissions can be managed dynamically from the admin panel

- 🎓 **Courses System**
  - Instructors can create and publish courses
  - Students can browse and purchase courses
  - Course structure supports multimedia content

- 💳 **Payments & Payouts**
  - Stripe integration for course purchases
  - PayPal payouts for instructor earnings
  - Revenue distribution logic for instructors

- 📦 **Media & Storage**
  - Multi-part upload support for course videos
  - AWS S3 for secure and scalable file storage

- ⚡ **Performance & Architecture**
  - Scalable backend design
  - Optimized database schema with Prisma ORM
  - Clean separation of concerns

---

## 🧰 Tech Stack

### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- Material UI

### Backend
- Node.js
- NestJS
- Prisma ORM
- PostgreSQL

### Infrastructure & Services
- AWS S3 (file storage)
- Stripe (payments)
- PayPal (payouts)

---

## 🏗️ Architecture Overview

- Modular monolithic backend using NestJS
- RESTful API design
- Prisma ORM for database access and type safety
- Role-based authorization middleware
- Service-oriented structure for business logic
- Secure environment-based configuration

---

## 🚀 Highlights

- Marketplace-like platform for online courses
- Instructor monetization with automated payouts
- Flexible permissions system for moderators
- Scalable media handling using S3
- Clean and maintainable full-stack architecture
- Designed with production and extensibility in mind

---

## 📂 Project Status

✔️ Core features completed  
🔄 Under active development  

### Coming Soon:
- 🎁 Offers system  
- 📥 Offline course download application  

---

## 📌 Notes

- Environment variables are required for Stripe, PayPal, AWS S3, and database configuration.
- The system is designed to support future expansion such as subscriptions and advanced analytics.
- Permissions system is dynamic and can be managed from the admin panel without code changes.

---