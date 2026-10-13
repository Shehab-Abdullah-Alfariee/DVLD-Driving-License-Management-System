# 🚘 DVLD -- Driving License Management System (C#)

A desktop-based **Driving License Management System (DVLD)** developed
with **C# and Windows Forms**, backed by a relational database in **SQL
Server**, and 3-Tier Architecture. The system organizes common driving-license workflows,
including people and user management, license applications, test
appointments, issuing and renewing licenses, and managing detained
licenses.

------------------------------------------------------------------------

## 🏗️ Architecture & Project Structure

The solution is strictly decoupled into 3 main layers to ensure maintainability, scalability, and code separation:

* **DVLD (Presentation Layer):** Windows Forms UI handling user interactions, validation, and visual components.
* **DVLD_Buisness (Business Logic Layer):** Encapsulates core business rules, validation logic, and workflows.
* **DVLD_DataAccess (Data Access Layer):** Handles direct database operations, ADO.NET connectivity, parameterized queries, and stored procedures.

------------------------------------------------------------------------

## 📌 Key Features

### 👥 People Management

-   Add, update, search, and view people records
-   Manage personal information and related country data
-   Reusable person information controls and forms

### 🔐 User Management & Authentication

-   User login screen
-   Add, update, view, and manage user accounts
-   Account settings and password-change workflow
-   User information and account management screens

### 📝 Application Management

-   Manage application types
-   Manage test types
-   Create local driving license applications
-   Process international driving license applications
-   Renew local driving licenses
-   Handle replacement requests for lost or damaged licenses

### 🧪 Driving Tests

-   Schedule test appointments
-   Record test results
-   Support retake workflows after failed tests
-   View test appointments and related application details

### 🪪 Drivers & License Services

-   Issue a driving license for the first time
-   View driver and license information
-   Review a person's license history
-   Renew driving licenses
-   Replace lost or damaged licenses

### 🚫 Detain & Release Licenses

-   Record license detention
-   Manage detained licenses
-   Release detained licenses

------------------------------------------------------------------------

## 🗄️ Database Overview

The database supports the main entities and relationships used by the
system, including:

-   People and countries
-   Users
-   Applications and application types
-   Local driving license applications
-   License classes
-   Test types, test appointments, and test results
-   Drivers and licenses
-   License renewal and replacement records
-   License detention and release records

------------------------------------------------------------------------

## 🧱 Technical Concepts

-   **Object-Oriented Programming (OOP)**
-   **Windows Forms** and reusable User Controls
-   **Events and Delegates** for communication between forms and
    controls
-   **Composition** to model relationships between objects
-   **Layered separation of responsibilities**, where implemented in the
    source code
-   **Relational database design** and data access
-   **Form-to-form data communication**

------------------------------------------------------------------------

## 🧰 Technologies Used

-   **Language:** C#
-   **Desktop UI:** Windows Forms
-   **Database:** Microsoft SQL Server
-   **Data Access:** Confirm the specific approach used in the source
    code (for example, ADO.NET)
-   **IDE:** Visual Studio
  
------------------------------------------------------------------------

## 📸 Some Of Interfaces

### 🖥️ Login Interface

<img width="1139" height="663" alt="image" src="https://github.com/user-attachments/assets/1dc9f19f-c282-4e72-a1c7-d4af832265d3" />


```
```
### 🖥️ Main Interface

<img width="1907" height="1024" alt="لقطة شاشة 2026-10-10 110342" src="https://github.com/user-attachments/assets/fc837bb8-bc51-4f5d-845d-955bcd41edfd" />

```
```
### 👥 People Management

<img width="1901" height="965" alt="لقطة شاشة 2026-10-10 110421" src="https://github.com/user-attachments/assets/26bdbfd9-46bc-4e98-b990-9aa8b2f9c2db" />

```
```
### 🔐 User Management

<img width="1222" height="974" alt="لقطة شاشة 2026-10-10 110451" src="https://github.com/user-attachments/assets/c6467d38-ad50-4a46-9073-2953eeeeb95b" />

```
```
### 📝 Driving License Applications

<img width="1788" height="976" alt="لقطة شاشة 2026-10-10 110523" src="https://github.com/user-attachments/assets/cb2e655e-f9fb-45be-8bb0-7f21abe50d1c" />

```
```
### 🧪 Add International License Applications

<img width="1116" height="978" alt="لقطة شاشة 2026-10-10 110621" src="https://github.com/user-attachments/assets/c0323eaa-0cb8-4569-9f6e-758dfdaec5ef" />

```
```
### 🪪 License Information

<img width="1091" height="697" alt="لقطة شاشة 2026-10-10 111254" src="https://github.com/user-attachments/assets/88e3c401-d49a-4965-a671-777a51975de1" />

```
```
### 🪪 License History

<img width="1341" height="1019" alt="لقطة شاشة 2026-10-10 111632" src="https://github.com/user-attachments/assets/df79ecd8-3d8f-4f93-9d7d-9622e089b48e" />

```
------------------------------------------------------------------------

## 🎯 Learning Objectives

This project provides practical experience with desktop application
development, object-oriented programming, relational database concepts,
reusable UI components, and the workflows involved in managing
driving-license services.

## 📚 Project Context

This project was developed as part of a structured programming learning
journey With D.Mohammed Abu-Hadhude at Programming Advices Academy >

