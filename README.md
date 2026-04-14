# 📚 Advanced Library & User Management System (ERP-Style)

A comprehensive administrative platform designed to manage library assets and system users with a high level of granular control. This project highlights specialized implementation of **Role-Based Access Control (RBAC)**, **System Auditing (Logs)**, and an optimized **AJAX-driven UI**.

## 🚀 Tech Stack & Skills

- **Backend:** ASP.NET Core 6.0 (MVC)
- **Database:** Microsoft SQL Server & Entity Framework Core
- **Security:** ASP.NET Core Identity (Roles & Permissions)
- **Design Pattern:** Repository Pattern & Dependency Injection
- **Frontend:** JavaScript, AJAX, Bootstrap Modals, and HTML/CSS

## 🚀 Core Features & Technical Implementation

### 🔐 Advanced Identity & RBAC
- **Triple Role System:** Implemented **SuperAdmin**, **Admin**, and **User** roles using **ASP.NET Core Identity**.
- **User Management:** Full administrative control over user accounts, including activation, deactivation, and profile management.
- **Seed Data:** Pre-configured system roles and administrative accounts for immediate testing.

### 📝 System Auditing (Activity Logs)
- **Action Tracking:** A specialized logging system that monitors all operations performed on the "Books" table.
- **Transparency:** Automatically records the **Event Type**, **Timestamp**, and the **Admin Identity** responsible for each change.

### 🛠️ Administrative Power (CMS Features)
- **Library Inventory:** Full CRUD operations for Books, Categories, and Sub-Categories using the **Repository Pattern**.
- **Dynamic Site Settings:** Control over website identity (Logo, Name, Description, and Social Links).
- **Page Content Management:** Dynamic control over Sliders, "About Us" content, and "Terms & Conditions".

### 🎨 Seamless UI with AJAX & Modals
- **In-Page CRUD:** Enhanced UX using **JavaScript** and **Bootstrap Modals** to manage data without full page reloads.
- **Asynchronous Operations:** Utilizing AJAX for a smooth, modern administrative experience.

---

## 📸 Project Screenshots

<div align="center">
  <img src="https://github.com/user-attachments/assets/340d8c60-827e-4774-90d8-3aad8823811f" width="48%" alt="Dashboard Overview" />
  <img src="https://github.com/user-attachments/assets/4400829f-a57e-45e2-a23c-88dfdd73dd0c" width="48%" alt="User Management" />
</div>

<br />

<div align="center">
  <img src="https://github.com/user-attachments/assets/81e93ec3-5cec-4688-bcda-d8057599020d" width="48%" alt="Book Inventory" />
  <img src="https://github.com/user-attachments/assets/f47fa734-e2e0-4756-9887-226170671372" width="48%" alt="System Logs" />
</div>

---

## 👥 User Roles & Access Control

### 🔑 Admin Credentials (For Testing)
- **Email:** `ibrahemtabaneh@gmail.com`
- **Password:** `123456`

---

## ⚙️ How to Run
1. Clone the repository.
2. Update the connection string in `appsettings.json`.
3. Run `Update-Database` in the Package Manager Console.
4. Launch the application (F5).

---
📫 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/ibrahem-tabaneh-249683249)
