<div align="center">

# 🎓 GENIUSAQILOS: Teacher Management System

![Flutter](https://img.shields.io/badge/Frontend-Flutter_3.41.9-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Language-Dart_3.11.5-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Supabase](https://img.shields.io/badge/Backend-Supabase_2.15.0-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

> An integrated, cross-platform mobile application developed to centralize and digitalize teacher administration for **Tadika Aqil Miqail**[cite: 1, 2].

</div>

---

## 📖 About The Project

Educational institutions often face operational bottlenecks due to decentralized record-keeping, inefficient manual leave processing, unstructured duty allocation, and subjective performance evaluations[cite: 1]. 

**GENIUSAQILOS** solves these challenges by providing an integrated solution with a relational cloud database that reduces administrative overhead and introduces standardized, automated workflows[cite: 1]. The system supports two primary user roles—**Teachers** and **Principals**—each equipped with specific interfaces and privileges to handle daily school operations securely[cite: 1].

---

## ✨ Core Modules & Features

The system is divided into six main functional modules to streamline institutional workflows[cite: 1]:

| Icon | Module Name | Core Features & Description |
| :---: | :--- | :--- |
| 🗂️ | **Teacher Records** | <ul><li>Store comprehensive personal info (IC Number, Contacts)[cite: 2].</li><li>Upload official documents (MyKad, Resume, Medical Check Up)[cite: 2].</li><li>Principals can track document verification statuses[cite: 3].</li></ul> |
| 🏖️ | **Leave Management** | <ul><li>Apply for 10 specific leave types (Annual, Medical, Maternity, etc.)[cite: 2].</li><li>Track remaining leave balances automatically[cite: 3].</li><li>Notify teachers for approval, rejections, and reminders[cite: 3].</li></ul> |
| 📋 | **Task & Duty Manager** | <ul><li>Auto-generate fair duty schedules for active staff[cite: 3].</li><li>Manage daily/monthly tasks (Cleaning, Arrival, Dismissal, Assembly)[cite: 2].</li><li>Provide clear checklists for tasks (e.g., Mop floors, empty bins)[cite: 2].</li></ul> |
| 🎓 | **Training Tracker** | <ul><li>Record training details across categories (Teaching Skills, Child Dev)[cite: 2].</li><li>Upload certificates, photos, and post-training reflections[cite: 2].</li><li>Monitor progress against annual minimum training targets[cite: 3].</li></ul> |
| 📈 | **Performance Tracker** | <ul><li>Evaluate teachers based on 10 KPI categories (Attendance, Pedagogy)[cite: 2].</li><li>Auto-calculate performance percentage scores from checklists[cite: 3].</li><li>Store warning letters and misconduct records centrally[cite: 3].</li></ul> |
| 🚨 | **Reporting System** | <ul><li>Submit reports easily (Damage, Bullying, IT/System problems)[cite: 2, 3].</li><li>Upload photographic evidence of incidents or hazards[cite: 3].</li><li>Support anonymous reporting and real-time status tracking[cite: 3].</li></ul> |

---

## 🛠️ Technology Stack

GENIUSAQILOS is built using a modern, scalable, and responsive technology stack[cite: 1]:

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend UI** | `Flutter` (v3.41.9) | Cross-platform mobile app framework[cite: 1]. |
| **Logic & Syntax** | `Dart` (v3.11.5) | Object-oriented language for logic and processing[cite: 1]. |
| **Backend & Auth** | `Supabase` (v2.15.0) | Backend-as-a-Service for user auth and role-based access[cite: 1]. |
| **Database** | `PostgreSQL` | Relational database mapping entities and ERD connections[cite: 1]. |
| **Cloud Storage** | `Supabase Storage` & `Cloudinary` | Secure storage for evidence, certificates, and profile images[cite: 1]. |
| **Version Control** | `GitHub` & `GitHub Desktop` | Code tracking, repository management, and collaboration[cite: 1]. |

---

## 🏛️ System Architecture

The application adopts a robust **Three-Tier Architecture**[cite: 1]:
1. **Presentation Layer:** The responsive Flutter mobile interface customized for Teacher and Principal roles[cite: 1].
2. **Application Layer:** The Dart-based business logic, implementing the Provider pattern to decouple UI screens from backend calculations[cite: 1].
3. **Data Layer:** Managed by Supabase (PostgreSQL) and Supabase Storage to securely handle user access, files, and role verifications[cite: 1].

---

## 👨‍💻 Development Team

This system was proudly developed by **Group Hackatoons** in collaboration with **Tadika Aqil Miqail** and **Universiti Teknologi Malaysia (UTM)**[cite: 1].

| Profile | Full Name | Matric Number |
| :---: | :--- | :--- |
| 👩‍💻 | **Lubna Al Haani Binti Radzuan** | `A23CS0107`[cite: 1] |
| 👩‍💻 | **Harini A/P Sangaran** | `A23CS0081`[cite: 1] |
| 👩‍💻 | **Nurul Asyikin Binti Khairul Anuar** | `A23CS0162`[cite: 1] |
| 👩‍💻 | **Jeanette Hauw Chandra** | `X25EC3020`[cite: 1] |
| 👩‍💻 | **Anis Safiyya Binti Janai** | `A23CS0049`[cite: 1] |

---
<div align="center">
  <i>Developed for the requirement of the Bachelor of Computer Science (Data Engineering) degree at Universiti Teknologi Malaysia (UTM).</i>[cite: 1]
</div>
