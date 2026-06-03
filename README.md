# transport_portal
A Python GUI-based Transportation Management System built with Tkinter and Pandas.

# 🚍 Transportation Management Portal (Python Tkinter + Pandas)

A simple **Transportation Management Portal** built using **Python**, **Tkinter GUI**, and **Pandas**.  
This project allows an **Admin** to manage vehicles and clients, and allows **Clients** to view available vehicles and book transport.

All records are stored using **CSV files** (acts as a small database system).

---

## ✨ Features

### 👨‍💼 Admin Dashboard
- Add new vehicles
- View all vehicles
- Add new clients
- View all clients
- Assign vehicles to clients
- View all bookings

### 👤 Client Portal
- Client login using Client ID
- View available vehicles
- Request/Book transport
- View personal bookings

---

## 🛠️ Technologies Used
- **Python**
- **Tkinter** (GUI)
- **Pandas** (Data handling)
- **CSV Files** (Data storage)

---

## 📂 Files Used for Storage
The program automatically creates these CSV files if they do not exist:

- `vehicles.csv` → Stores vehicle details  
- `clients.csv` → Stores client details  
- `bookings.csv` → Stores booking records  

---

## 🚀 How to Run the Project

### 1️⃣ Install Required Libraries
Make sure you have Python installed, then install pandas:

'''bash
pip install pandas
'''
### 2️⃣ Run the Program
python transportation_portal3.py

🧾 CSV Format
vehicles.csv
vehicle_id      type      status
V101	          Bus	      Available
clients.csv
client_id      name      contact
C101	         John	     987654321
bookings.csv
client_id	vehicle_id
C101	    V101

🔐 Login Information
Admin Login
(Admin login directly opens dashboard)
Client Login
Client must enter a valid Client ID added by admin.

Example:
Client ID: C101

📌 Project Highlights

1. Simple and user-friendly GUI interface
2. File-based database using CSV
3. Separate admin and client functionalities
4. Real-time vehicle booking status update
