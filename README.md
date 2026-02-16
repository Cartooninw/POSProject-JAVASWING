## 🧾 POS System (Java Swing)
<img width="1122" height="624" alt="Screenshot 2026-02-16 205026" src="https://github.com/user-attachments/assets/e725fece-4364-4aa5-aeb1-ce40e3ce67fa" />
A desktop-based Point of Sale (POS) System built with Java Swing.
This project supports multi-user management, order processing, item management, and revenue tracking using a simple file-based database.

### 📌 Overview

This project simulates a small shop POS system that allows staff or admin to:

- Login and manage users
- Add / edit / delete menu items
- Create and process customer orders
- Calculate total price automatically
- View and filter revenue records
- Store all data in local files (no external database)
- 
It is designed for learning OOP, GUI development, and file handling in Java.

### 🛠️ Tech Stack
Language: Java
GUI Framework: Java Swing
Data Storage: Text files (.txt)
Build Tool: Ant (NetBeans project)

### 🧩 Features
- 👤 User System
- Register new users
-Login system
- Multi-user management
- Admin and normal user roles
- 🛒 Order Management
- Create new orders
- Select items from menu
- Auto calculate total price
- Save order records
- 🍔 Item Management
- Add new item
- Edit item
- Delete item
- Store items in itemlist.txt
- 📊 Revenue System
- Record all transactions
- View revenue history
- Filter by date
- Display revenue summary

### 📂 Project Structure
```
src/
│
├── Data/
│   ├── DataBase.java
│   ├── itemlist.txt
│   ├── recordRevenue.txt
│   └── userdata.txt
│
├── Main/
│   └── Main.java
│
├── MainUser/
│   ├── Login.java
│   ├── Register.java
│   ├── Userinterface.java
│   └── MultiUserManager.java
│
├── Shopmain/
│   ├── AdminInterface.java
│   ├── AddItem.java
│   ├── Edititem.java
│   └── InterOrder.java
│
└── Record/
    ├── CheckOrder.java
    ├── DateSearch.java
    └── SelfCal.java
```
### ▶️ How to Run
Option 1: Using NetBeans (recommended)

#### Open NetBeans

#### Click Open Project

#### Select this project folder

#### Click Run Project

### Option 2: Using Terminal (Ant)
```
ant run
```
### 🧪 Default Data Files

- The system uses text files as database:
- itemlist.txt → store all menu items
- userdata.txt → store user accounts
- recorddata.txt → store order history
- recordRevenue.txt → store revenue logs

## 📸 Example Screens 
### Admin Interface
<img width="1023" height="620" alt="Screenshot 2026-02-16 204957" src="https://github.com/user-attachments/assets/9aed1bb2-9f9c-4699-8ca7-4f4a7779ec45" />

### Shop Interface
<img width="1122" height="624" alt="Screenshot 2026-02-16 205026" src="https://github.com/user-attachments/assets/e725fece-4364-4aa5-aeb1-ce40e3ce67fa" />

### Admin Alerts
<img width="463" height="266" alt="Screenshot 2026-02-16 204944" src="https://github.com/user-attachments/assets/c77b878b-3f49-4bd0-bad5-e91ae1cff25f" />





## 🎯 Learning Objectives

### This project helped me understand:

- Java Swing GUI design

- Object-Oriented Programming (OOP)

- File I/O for data storage

- Basic system architecture

- User management system

- Order and revenue tracking logic

## 🚀 Future Improvements

- Connect to real database (MySQL / PostgreSQL)

- Add REST API backend (Spring Boot)

- Export reports as PDF

- Improve UI/UX design

- Add authentication security (password hashing)
