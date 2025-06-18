# 🫀 Organ Donor Management System

A full-featured desktop application to manage organ donors, recipients, and organ donation workflows. Developed using **C# (ASP.NET Windows Forms)** and **SQL Server**, this project aims to streamline organ request handling, matching, notifications, and reporting for a hospital or medical institution.

---

## 💡 Project Overview

This system helps manage:

- Donor and recipient registrations  
- Organ donation requests and status tracking  
- Automated organ compatibility matching  
- Role-based access for users and administrators  
- Notifications via SMS and email  
- Expiry tracking for stored organs  
- Activity and donation reports via Crystal Reports

---

## 🛠️ Tech Stack

- **Frontend:** Windows Forms (C#)
- **Backend:** ASP.NET
- **Database:** Microsoft SQL Server
- **Reporting:** Crystal Reports
- **Other:** SMTP for email, SMS API for notifications

---

## 🔐 Features

✅ Secure login with role-based access (Admin/User)  
✅ Register and manage donors and recipients  
✅ CRUD operations on users, organs, and requests  
✅ Organ matching logic based on blood type and organ type  
✅ Automatic expiry alerts for stored organs  
✅ Email and SMS alerts for donation match and status updates  
✅ Crystal Reports for data visualization and printing  

---


---

## 🧠 Organ Matching Logic

The matching algorithm considers:
- Blood group compatibility (e.g. A+, O-)
- Organ type (heart, kidney, etc.)
- Urgency or time of request

This ensures fair and medically appropriate matches.

---

## 🗂️ Project Structure
OrganDonorManagementSystem/
│
├── Forms/ # All Windows Forms UI screens
├── Reports/ # Crystal Reports files
├── Database/ # SQL scripts and schema
├── Utils/ # Utility classes like MailService, SMSService
├── Program.cs # Entry point
├── app.config # Configuration settings
└── README.md # Project documentation



---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/AdityaChopade11/organ-donor-management-system.git
Open the solution (.sln) file in Visual Studio.

Restore dependencies if needed.

Setup SQL Server:

Run the SQL script in the /Database folder to create tables.

Update the connection string in app.config.

Run the project.

| Role  | Username | Password |
| ----- | -------- | -------- |
| Admin | admin    | admin123 |
| User  | user1    | user123  |


Feel free to fork, contribute, or raise issues for enhancements!


---

Let me know if you want to add a **live demo video**, **setup tutorial**, or auto-generate the database schema file!




🙋‍♂️ Author
Aditya Chopade
📧 adityachopade.dev@gmail.com




