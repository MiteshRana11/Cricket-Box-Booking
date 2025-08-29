# 🏏 Cricket Box Booking System  

A **Simple Online Sports Complex Booking System** that allows **Admins, Staff, Registered Clients, and Guests** to interact with the platform.  
This project makes booking facilities easier and ensures **no scheduling conflicts** between clients.  

---

## ✨ Features  

### 👨‍💼 Admin & Staff Panel  
- **Admin**
  - Full control over system management  
  - Manage facilities, bookings, and clients  
- **Staff**
  - Limited access to assist in managing bookings  

### 👤 Clients  
- Register and log in to the system  
- Book facilities on their desired date (no overlaps allowed)  
- View their **booking history**  

### 🌐 Public / Guests  
- Explore available facilities  
- Learn about the system without registering  

---

## ⚡ Requirements  
- Local Web Server (**XAMPP** / **WAMP**)  
- PHP 7.x or higher  
- MySQL Database  
- Web Browser  

---

## 🛠️ Installation / Setup Guide  

1. **Enable GD Library**  
   - Open your XAMPP/WAMP’s `php.ini` file  
   - Uncomment/enable the line for GD library  

2. **Start Services**  
   - Open XAMPP/WAMP Control Panel  
   - Start **Apache** and **MySQL**  

3. **Prepare Project Files**  
   - Extract the downloaded source code zip file  
   - For **XAMPP** → paste into `htdocs` folder  
   - For **WAMP** → paste into `www` folder  

4. **Database Setup**  
   - Go to: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)  
   - Create a new database named **`scbs_db`**  
   - Import the SQL file: `database/scbs_db.sql`  

5. **Run the Project**  
   - Open in browser:  
     ```
     http://localhost/scbs/
     ```

---

## 🔑 Default Admin Login  
- **Username:** `admin`  
- **Password:** `admin123`  

---

## 📸 Screenshot  
👉 *(Add a screenshot of your project here for more appeal!)*  

---

## 👨‍💻 Author  
Developed by **[Your Name](https://github.com/your-username)**  

---
