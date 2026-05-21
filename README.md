# Smart Parking System 🚗

A CLI-based Multi-Level Smart Parking System developed using Java and Object-Oriented Programming concepts.

---

## 📌 Project Overview

This project simulates a real-world smart parking management system that handles:

- Vehicle Entry & Exit
- Dynamic Slot Allocation
- Multi-floor Parking
- Parking Fee Calculation
- Occupancy Tracking
- Slot Release & Reallocation

The system is designed as a command-line interface (CLI) application using Java.

---

## 🚀 Features

### ✅ Vehicle Management
- Register vehicle entry
- Prevent duplicate vehicle parking
- Vehicle exit handling

### ✅ Smart Slot Allocation
- Multi-floor support
- Slot allocation based on vehicle type:
  - BIKE
  - CAR
  - TRUCK
- First-fit allocation strategy

### ✅ Billing System
- Tracks entry and exit time
- Calculates parking fee based on duration

### ✅ Parking Status
- Displays occupied and available slots
- Shows vehicle details for occupied slots

---

## 🛠 Technologies Used

- Java
- OOP Concepts
- Collections Framework
- IntelliJ IDEA
- Git & GitHub

---

## 📂 Project Structure

```plaintext
SmartParkingSystem/
│
├── src/
│   ├── Main.java
│   ├── ParkingLot.java
│   ├── Floor.java
│   ├── ParkingSlot.java
│   ├── Vehicle.java
│   ├── Ticket.java
│   └── FeeCalculator.java
```

---

## 🧠 OOP Concepts Used

- Classes & Objects
- Encapsulation
- Abstraction
- Composition
- Collections (ArrayList, HashMap)

---

## ▶️ How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/SmartParkingSystem.git
```

### 2️⃣ Open in IntelliJ IDEA

- Open IntelliJ IDEA
- Select **Open Project**
- Choose the project folder

### 3️⃣ Run Application

Run:

```plaintext
Main.java
```

---

## 💻 Sample Output

```plaintext
===== SMART PARKING SYSTEM =====

1. Vehicle Entry
2. Vehicle Exit
3. View Parking Status
4. Exit

Enter choice: 1

Enter Vehicle Number: TN10AB1234
Enter Vehicle Type (BIKE/CAR/TRUCK): CAR

Vehicle Parked Successfully!
Floor: 1
Slot: 3
```

---

## 📊 Business Rules Implemented

- No duplicate vehicle entries
- Vehicle must match slot type
- Slot released after vehicle exit
- Accurate fee calculation
- Dynamic slot allocation

---

## 🔮 Future Enhancements

- GUI Version using JavaFX
- Database Integration (MySQL)
- Online Slot Booking
- QR-based Entry System
- Admin Dashboard
- Payment Gateway Integration

---

## 👨‍💻 Author

**Narasimhan Seenu**

---

## 📜 License

This project is developed for educational and learning purposes.
