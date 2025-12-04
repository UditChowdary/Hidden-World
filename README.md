# Hidden-World – Travel Management System

Hidden-World is a full-stack PHP-based Travel Management System that allows users to explore destinations, book trips, and browse galleries, while providing admins full control over content, bookings, and user management.  
It integrates MySQL for data storage and uses a Bootstrap-based responsive frontend.

---

## 🚀 Features

**✅ User Features**

- Register / Login  
- Browse destinations  
- View trip details  
- Submit booking requests  
- Explore gallery images  
- Contact form  

---

**🛠️ Admin Features**

- Admin authentication  
- Manage destinations & places  
- Add / update / delete travel packages  
- Upload gallery images  
- Manage bookings  
- View registered users  
- Dashboard with statistics  

---

## 🧩 Tech Stack

### Frontend:

- HTML5  
- CSS3  
- JavaScript / jQuery  
- Bootstrap  

### Backend:

- PHP (Procedural)  
- MySQL  

### Libraries / Plugins:

- jQuery plugins  
- Owl Carousel  
- DataTables  
- Font Awesome  
- Various admin panel UI scripts  

---

## 📁 Project Structure

<img width="557" height="424" alt="image" src="https://github.com/user-attachments/assets/92eeb176-193d-451d-bc12-6b5fe84c28bf" />

---

## ⚙️ Installation & Setup

### 1️⃣ Requirements

- PHP 7+  
- MySQL / MariaDB  
- Apache or any PHP-enabled server  
- Composer (optional)  

### 2️⃣ Setup Steps

1. Extract the project folder into your server directory:

```
htdocs/Project
```

2. Import the database:  
   - Open phpMyAdmin  
   - Create a database (e.g., `travelms`)  
   - Import the provided SQL file  

3. Configure database  
   Open `config.php` and update credentials:

```
$servername = "localhost";
$username   = "root";
$password   = "";
$dbname     = "travelms";
```

4. Run the project

👉 User Website:  
http://localhost/Project/

👉 Admin Panel:  
http://localhost/Project/admin/

---

## 🔐 Default Admin Credentials

*(If included in database; otherwise create manually)*

- **Username:** admin  
- **Password:** admin123  

---

## 🔮 Future Enhancements

- Online payment integration  
- Email notifications  
- User profile dashboard  
- Review & rating system  
- REST API endpoints  

---

## 🙌 Author

**Udit Chowdary Jasti**
