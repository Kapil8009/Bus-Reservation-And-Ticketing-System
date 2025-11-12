Here’s a **professional and clear README file** you can include for your **Java Bus Reservation System (KapilBus)** project 👇

---

# 🚌 KapilBus – Bus Reservation and Ticketing System

## 📋 Project Overview

**KapilBus** is a console-based Java application designed to simulate a **Bus Reservation and Ticketing System**.
Users can **register, log in, book tickets, view available destinations, make payments, and check passenger details** through a text-based menu system.

This project demonstrates the use of **Java control structures**, **arrays**, **loops**, **user input handling**, and **basic object-oriented programming concepts**.

---

## 🚀 Features

### 1️⃣ User Registration

* New users can register by providing their name, mobile number, username, and password.
* Includes input validation for mobile number and password confirmation.

### 2️⃣ User Login

* Registered users can log in to access the main menu.
* Allows up to 3 login attempts.

### 3️⃣ Bus Reservation System

* View available destinations and fares.
* Book seats for selected destinations.
* Handle discounted passengers (e.g., Students, Senior Citizens, PWDs).
* Automatically updates available seats after booking.

### 4️⃣ Payment and Billing

* Calculates total fare and discounts.
* Allows users to make payments and receive change.
* Prevents duplicate payments for the same passenger.

### 5️⃣ View Passenger Details

* Search and view passenger details including fare, destination, payment status, and total fare.

### 6️⃣ Exit System

* Option to safely exit the system at any time.

---

## 🧰 Technologies Used

| Technology                              | Purpose                                    |
| --------------------------------------- | ------------------------------------------ |
| **Java (Core Java)**                    | Main programming language                  |
| **BufferedReader**                      | To take input from users                   |
| **Arrays**                              | To store passenger, fare, and booking data |
| **Control Structures (if, for, while)** | Logic and flow control                     |
| **Console (CLI)**                       | User interface                             |

---

## ⚙️ How to Run the Project

1. **Install Java (JDK 8 or higher)**
   Make sure Java is installed on your system. You can check using:

   ```bash
   java -version
   ```

2. **Save the Program File**
   Save the source code as:

   ```
   KapilBus.java
   ```

3. **Compile the Program**

   ```bash
   javac KapilBus.java
   ```

4. **Run the Program**

   ```bash
   java KapilBus
   ```

5. **Follow the On-Screen Instructions**

   * Choose to **Login** or **Register**.
   * After login, choose from menu options to book, view, or pay.

---

## 🧮 Sample Destinations and Fares

| Destination | Fare (Php) | Seats Available |
| ----------- | ---------- | --------------- |
| Kanpur      | 400        | 20              |
| Pokharayan  | 300        | 20              |
| Gauri Karan | 600        | 20              |
| Gorakhpur   | 300        | 20              |
| Delhi       | 700        | 20              |

> 💡 *PWD, Student, and Senior Citizen passengers get a 20% discount.*

---

## 💾 Future Enhancements

* Integrate with **MySQL database** for storing user and booking data permanently.
* Develop a **GUI version** using Java Swing or JavaFX.
* Add **seat number selection** and **ticket printing**.
* Implement **admin panel** for managing bus routes and fares.

---

## 🧑‍💻 Developer

**Name:** Kapil
**Project:** Bus Reservation and Ticketing System
**Language:** Java
**Version:** 1.0

---
