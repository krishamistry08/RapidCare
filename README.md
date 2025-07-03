# 🏥 RapidCare – Appointment & Bed Booking System

**RapidCare** is a web-based system that allows patients to easily **book doctor appointments** and **reserve hospital beds** in advance, helping hospitals streamline admissions and reduce last-minute panic.

## ✨ Features

- 📅 **Doctor Appointment Booking**
  - Select doctor, date, and time.
  - Real-time availability check.
  
- 🛏️ **Hospital Bed Booking**
  - View available beds visually.
  - Book a bed like a movie seat layout.
  - Red = Booked, Green = Available.

- 🔐 **Admin Panel**
  - View and manage appointments and bed bookings.
  - Secure backend access.

## 💻 Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL (via XAMPP)

## 📁 Folder Structure

```plaintext
/rapidcare
├── index.html              # Home page
├── appointment.php         # Appointment booking form
├── bed-booking.php         # Bed booking layout
├── admin/                  # Admin dashboard pages
├── db/                     # Database connection & SQL files
├── css/                    # Stylesheets
├── js/                     # JavaScript for UI interaction
└── README.md

🚀 How to Run the Project
Follow these steps to set up and run RapidCare on your local machine using XAMPP:

1.Download and Extract the Project

   Download the ZIP file of this project from GitHub.

   Extract the contents into the htdocs folder of your XAMPP installation (usually located at C:\xampp\htdocs).

   Rename the folder to rapidcare (if it's not already).

2.Start XAMPP

   Open XAMPP Control Panel.

   Start Apache and MySQL.

3.Set Up the Database

   Open your browser and go to http://localhost/phpmyadmin

   Click New, and create a database named: myhmsdb

   Click on the myhmsdb database.

   Click Import, then choose the .sql file provided with the project.

   Import the database.

4.Run the Project

   Open your browser and visit:
   👉 http://localhost/rapidcare

   The homepage of RapidCare should load with appointment and bed booking options.
