
# 🛒 BHARAT-APP

> **ALL IN ONE E-COMMERCE WEBSITE** - A comprehensive e-commerce platform with all essential services for day-to-day shopping needs.

---

## 📖 Overview

BHARAT-APP is a fully functional e-commerce website prototype designed as a final year Software Engineering project. It provides a complete online shopping experience with multiple services and features required for modern e-commerce operations. This is a server-based website built with PHP and MySQL, perfect for demonstrating real-world web application concepts.

**Project Submitted By:** Ankit Ranjan Bhoi  
**Institution:** Kristu Jayanti College (Batch 2023-2026)  
**Project Type:** Software Engineering Subject - Final Year Prototype

---

## ✨ Features

- 🛍️ Complete product catalog and browsing
- 🛒 Shopping cart functionality
- 💳 Secure checkout and payment processing
- 👤 User authentication and account management
- 📦 Order tracking and management
- 🔍 Advanced product search and filtering
- ⭐ Product reviews and ratings
- 💰 Multiple payment options
- 📱 Responsive and user-friendly design
- 🔐 Secure user data management
- 📊 Admin dashboard for management

---

## 🛠️ Technologies Used

- **Backend:** PHP
- **Database:** MySQL
- **Frontend:** HTML5, CSS3, JavaScript
- **Server:** Apache (XAMPP)
- **Version Control:** Git

---

## 📁 Project Structure

```
BHARAT-APP/
├── config/              # Database configuration
├── includes/            # PHP includes and headers
├── pages/               # Main application pages
├── products/            # Product data and management
├── orders/              # Order management
├── users/               # User authentication and profiles
├── admin/               # Admin dashboard
├── assets/
│   ├── css/             # Stylesheets
│   ├── js/              # JavaScript files
│   └── images/          # Images and icons
├── uploads/             # User and product uploads
└── index.php            # Main entry point
```

---

## 🚀 Getting Started

### Prerequisites

- **XAMPP Server** (includes Apache and MySQL)
- **Web Browser** (Chrome, Firefox, Safari, Edge)
- **Git** (optional, for version control)

### Installation Steps

1. **Download and Install XAMPP**
   - Download from: [https://www.apachefriends.org/](https://www.apachefriends.org/)
   - Install XAMPP on your system

2. **Clone/Download the Project**
   ```bash
   git clone https://github.com/AnkitRB-2006/BHARAT-APP.git
   ```

3. **Place Project in XAMPP Directory**
   - Copy the `BHARAT-APP` folder to: `C:\xampp\htdocs\`
   - Final path should be: `C:\xampp\htdocs\BHARAT-APP`

4. **Start XAMPP Services**
   - Open XAMPP Control Panel
   - Start **Apache** server ✓
   - Start **MySQL** server ✓

5. **Set Up Database**
   - Open phpMyAdmin: `http://localhost/phpmyadmin/`
   - Create a new database named `bharat_app`
   - Import the database schema from the project (if provided)

6. **Configure Database Connection**
   - Open `config/db.php` or equivalent
   - Update database credentials if needed:
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $database = "bharat_app";
     ```

7. **Access the Application**
   - Open your browser
   - Go to: `http://localhost/BHARAT-APP/`
   - Start shopping! 🎉

---

## 📖 Usage Guide

### For Customers
- Browse products by category
- Search for specific products
- Add items to shopping cart
- Proceed to checkout
- Place orders and track status
- View order history

### For Administrators
- Access admin dashboard
- Manage product inventory
- Monitor orders
- Manage user accounts
- View sales reports

---

## ⚙️ Troubleshooting

| Issue | Solution |
|-------|----------|
| **Page not found (404)** | Ensure XAMPP is running and file is in `C:\xampp\htdocs\BHARAT-APP` |
| **Database connection error** | Check MySQL is running and database credentials in `config/db.php` are correct |
| **Apache not starting** | Check if port 80 is already in use by another application |
| **MySQL not starting** | Check if port 3306 is already in use |
| **Blank page** | Enable PHP error reporting or check Apache error logs |

---

## 📝 License

This project is provided as-is for educational purposes. 

---

## 🤝 Contributing

This is a prototype/academic project. Suggestions and improvements are welcome:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 🙋 Support & Contact

For questions, issues, or suggestions:

- **GitHub Issues:** [Report a bug or suggestion](https://github.com/AnkitRB-2006/BHARAT-APP/issues)
- **Email:** Feel free to reach out!

---

## ⚠️ Important Notes

- ⚡ **This is a prototype/academic project**, not a production-ready application
- 🔒 Implement additional security measures before using in production
- 📱 Optimize for mobile devices if deploying publicly
- 🗄️ Regular database backups are recommended
- 🔑 Change default credentials and implement proper authentication

---

## 👤 Author

**Ankit Ranjan Bhoi**  
📚 Kristu Jayanti College  
📅 Batch: 2023-2026  

---

Made with ❤️ as a Software Engineering Final Year Project
