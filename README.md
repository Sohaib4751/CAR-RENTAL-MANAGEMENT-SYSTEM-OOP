# CAR-RENTAL-MANAGEMENT-SYSTEM-OOP
# 🚗 Car Rental Management System

A comprehensive C++ console-based application that manages vehicle rentals, customer data, and rental transactions using object-oriented programming principles.

---

## 📋 Overview

The **Car Rental Management System** is designed to streamline the process of renting cars by providing tools to manage vehicles, customers, and transactions. The system supports various vehicle types, maintains rental history, and secures access through user authentication. It uses file handling to ensure data persistence across sessions.

---

## ✨ Key Features

### 🚘 Vehicle Management
- Add new vehicles (Sports Cars, Daily Use Cars, Electric Cars)
- Prevent duplicate chassis numbers
- Edit vehicle details (name, color, transmission)
- View detailed vehicle information and rental history

### 👤 Customer Management
- Add and manage customer profiles (name, CNIC, phone, email, address)
- Search and edit customer information
- Track each customer's rental history and dues

### 📄 Rental Transactions
- Rent vehicles for specific durations
- Calculate rental cost and advance payments
- Extend rentals and process vehicle returns (with damage claims)
- Generate detailed bills for each rental

### 🔐 User Authentication
- Role-based login system (Owner and Employee)
- Secure access to sensitive operations

### 💾 Data Persistence
- Store all customer and vehicle data using file handling
- Ensure session-to-session data consistency with `.txt` files

---

## 🧱 Technical Implementation

### 🧩 Object-Oriented Design
- `Vehicle` (Base Class): Common attributes and methods  
- `sportscar`, `dailyusecar`, `ecar` (Derived Classes): Fuel-type specific  
- `Customer`: Manages customer info and rental tracking

### 🧮 Static Members
- Tracks total rental days across all vehicles

### 📂 File Handling
- Vehicle and customer data saved to and loaded from files using `fstream`

### 🖥 Console Interface
- Intuitive text-based UI for ease of navigation and operations

---

## 🛠 Technologies Used

- **Language**: C++
- **Paradigm**: Object-Oriented Programming (OOP)
- **Tools**: File handling using standard I/O libraries
- **Interface**: Console (CLI)

---

## 🚀 Future Enhancements

- GUI integration (using Qt or another framework)
- Database support (MySQL or SQLite) instead of text files
- Online booking and digital payment support
- Admin panel with real-time analytics

---

## 📝 License

This project is developed **for educational purposes as part of coursework at FAST-NUCES**.  
It demonstrates core OOP concepts, file handling, and system-level design in C++.
