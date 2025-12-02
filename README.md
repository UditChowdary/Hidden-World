# Hidden-World
**🌍 Travel Management System**

A full-stack PHP web application for exploring destinations, managing trips, handling bookings, and providing admin control over content, users, and packages.

**📌 Overview**

This Travel Management System allows users to browse tourist destinations, view details, create accounts, and book travel packages.
Admins can manage destinations, trips, galleries, users, bookings, and upload media.

The project includes:

User-facing website (Home, Destinations, Gallery, Booking, Contact)

Admin dashboard (Manage Users, Trips, Places, Gallery, Bookings)

MySQL database integration

File upload system for images

Responsive UI with Bootstrap

**🧭 Features**

**✔️ User Features**

Register / Login

Browse destinations

View trip details

Submit booking requests

View gallery images

Contact form

**✔️ Admin Features**

Admin authentication

Manage destinations & places

Add/update/delete travel packages

Upload gallery images

Manage bookings

View and manage registered users

Dashboard with statistics

**🛠️ Tech Stack**

**Frontend**

HTML5

CSS3

JavaScript / jQuery

Bootstrap

**Backend**

PHP (Procedural)

MySQL Database

Libraries / Plugins

jQuery plugins

Owl Carousel

DataTables

Font Awesome

Various admin panel UI scripts

**📂 Project Structure**

<img width="557" height="424" alt="image" src="https://github.com/user-attachments/assets/92eeb176-193d-451d-bc12-6b5fe84c28bf" />


**⚙️ Installation & Setup**

**1️⃣ Requirements**

PHP 7+

MySQL / MariaDB

Apache or any PHP-enabled server

Composer (optional but recommended)

**2️⃣ Setup Steps**

1. Extract the project folder

Place it in your server directory:

htdocs/Project

2. Import the database

Open phpMyAdmin

Create a database (e.g., travelms)

Import the SQL file (if provided)

3. Configure database

Open config.php and update your DB credentials:

$servername="localhost";
$username="root";
$password="";
$dbname="travelms";

4. Run the project

Visit:

http://localhost/Project/


Admin URL:

http://localhost/Project/admin/

**🔐 Default Admin Credentials**

(If provided in DB; otherwise you must create manually)

Username: admin
Password: admin123  (or as set in database)

**🎯 Future Enhancements**

Online payment integration

Email notifications

User profile dashboard

Review & rating system

REST API endpoints

**👨‍💻 Author**

Udit Chowdary Jasti
