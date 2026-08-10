<div align="center">

# 🎓 GENIUSAQILOS: Teacher Management System

![Flutter](https://img.shields.io/badge/Frontend-Flutter_3.41.9-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Language-Dart_3.11.5-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Supabase](https://img.shields.io/badge/Backend-Supabase_2.15.0-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

> An integrated, cross-platform mobile application developed to centralize and digitalize teacher administration for **Tadika Aqil Miqail**.

</div>

---

## 📖 About The Project

Educational institutions often face operational bottlenecks due to decentralized record-keeping, inefficient manual leave processing, unstructured duty allocation, and subjective performance evaluations. 

**GENIUSAQILOS** solves these challenges by providing an integrated solution with a relational cloud database that reduces administrative overhead and introduces standardized, automated workflows. The system supports two primary user roles—**Teachers** and **Principals**—each equipped with specific interfaces and privileges to handle daily school operations securely.

---

## ✨ Core Modules & Features

The system is divided into six main functional modules to streamline institutional workflows[cite: 1]:

| Icon | Module Name | Core Features & Description |
| :---: | :--- | :--- |
| 🗂️ | **Teacher Records** | <ul><li>Store comprehensive personal info (IC Number, Contacts)[cite: 2].</li><li>Upload official documents (MyKad, Resume, Medical Check Up).</li><li>Principals can track document verification statuses.</li></ul> |
| 🏖️ | **Leave Management** | <ul><li>Apply for 10 specific leave types (Annual, Medical, Maternity, etc.)[cite: 2].</li><li>Track remaining leave balances automatically.</li><li>Notify teachers for approval, rejections, and reminders.</li></ul> |
| 📋 | **Task & Duty Manager** | <ul><li>Auto-generate fair duty schedules for active staff[cite: 3].</li><li>Manage daily/monthly tasks (Cleaning, Arrival, Dismissal, Assembly).</li><li>Provide clear checklists for tasks (e.g., Mop floors, empty bins).</li></ul> |
| 🎓 | **Training Tracker** | <ul><li>Record training details across categories (Teaching Skills, Child Dev).</li><li>Upload certificates, photos, and post-training reflections.</li><li>Monitor progress against annual minimum training targets.</li></ul> |
| 📈 | **Performance Tracker** | <ul><li>Evaluate teachers based on 10 KPI categories (Attendance, Pedagogy).</li><li>Auto-calculate performance percentage scores from checklists.</li><li>Store warning letters and misconduct records centrally.</li></ul> |
| 🚨 | **Reporting System** | <ul><li>Submit reports easily (Damage, Bullying, IT/System problems).</li><li>Upload photographic evidence of incidents or hazards[cite: 3].</li><li>Support anonymous reporting and real-time status tracking.</li></ul> |

---

## 🛠️ Technology Stack

GENIUSAQILOS is built using a modern, scalable, and responsive technology stack:

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend UI** | `Flutter` (v3.41.9) | Cross-platform mobile app framework. |
| **Logic & Syntax** | `Dart` (v3.11.5) | Object-oriented language for logic and processing. |
| **Backend & Auth** | `Supabase` (v2.15.0) | Backend-as-a-Service for user auth and role-based access. |
| **Database** | `PostgreSQL` | Relational database mapping entities and ERD connections. |
| **Cloud Storage** | `Supabase Storage` & `Cloudinary` | Secure storage for evidence, certificates, and profile images. |
| **Version Control** | `GitHub` & `GitHub Desktop` | Code tracking, repository management, and collaboration. |

---

## 🏛️ System Architecture

The application adopts a robust **Three-Tier Architecture**:
1. **Presentation Layer:** The responsive Flutter mobile interface customized for Teacher and Principal roles.
2. **Application Layer:** The Dart-based business logic, implementing the Provider pattern to decouple UI screens from backend calculations.
3. **Data Layer:** Managed by Supabase (PostgreSQL) and Supabase Storage to securely handle user access, files, and role verifications.

---

## 👨‍💻 Development Team

This system was proudly developed by **Group Hackatoons** in collaboration with **Tadika Aqil Miqail** and **Universiti Teknologi Malaysia (UTM)**.

| Profile | Full Name | Matric Number |
| :---: | :--- | :--- |
| 👩‍💻 | **Lubna Al Haani Binti Radzuan** | `A23CS0107` |
| 👩‍💻 | **Harini A/P Sangaran** | `A23CS0081` |
| 👩‍💻 | **Nurul Asyikin Binti Khairul Anuar** | `A23CS0162` |
| 👩‍💻 | **Jeanette Hauw Chandra** | `X25EC3020` |
| 👩‍💻 | **Anis Safiyya Binti Janai** | `A23CS0049` |

---
<div align="center">
  <i>Developed for the requirement of the Bachelor of Computer Science (Data Engineering) degree at Universiti Teknologi Malaysia (UTM).</i>
</div>
