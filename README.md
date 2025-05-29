# 🏥 MediCore – Hospital Management System

**MediCore** is a hospital management system built using **Java (NetBeans IDE)** and **Oracle SQL*Plus**. It is designed to digitize and streamline hospital operations including patient management, doctor supervision, treatment tracking, billing, and room allocations.

---

## 🔍 Problem Statement

Manual handling of hospital data such as patient records, treatments, and billing is often inefficient and error-prone. MediCore solves this by implementing a **centralized relational database** that ensures data consistency, supports normalization, and simplifies hospital workflows.

---

## 🧩 Key Modules and Features

- **Patient Management**: Store personal info, medical history, room allocation.
- **Doctor & Intern Handling**: Track specializations, supervising relationships, and departmental assignments.
- **Treatment Module**: Manage treatment types, costs, and links to both patients and doctors.
- **Billing System**: Generate and store bills per patient.
- **Medication Module**: Track prescribed medication with dosage and side effects.
- **Room & Department Allocation**: Efficient room tracking and departmental supervision.
- **Login System**: Includes user authentication with success/error pop-ups.
  
---

## 🗃️ Database Design

- 15+ normalized relations following **1NF, 2NF, and 3NF**.
- Key tables: `Patient`, `Doctor`, `Room`, `Bill`, `Medication`, `Treatment`, `Department`.
- Handles many-to-many and one-to-many relationships via bridge tables.
- Uses **JDBC** to connect Java with Oracle DB.

---

## 🛠️ Tech Stack

- **Frontend**: Java Swing (NetBeans IDE)
- **Backend**: Oracle SQL*Plus
- **Connectivity**: JDBC

---

