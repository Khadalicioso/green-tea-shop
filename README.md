# 🍵 Green Tea Shop

A modern e-commerce platform specialized in premium green tea products, featuring both customer-facing interfaces and a comprehensive admin panel.

## ✨ Features

### 👥 Customer Features

- Browse extensive tea catalog
- User account management
- Secure shopping cart
- Order tracking
- Product reviews and ratings
- Responsive design for all devices

### 👨‍💼 Admin Panel

- Dashboard with real-time analytics
- Product management (CRUD operations)
- User management
- Order processing and tracking
- Inventory management
- Sales reports

## 🛠️ Tech Stack

- **Frontend:**

  - HTML5
  - CSS3
  - JavaScript
  - Responsive Design
  - SweetAlert for notifications

- **Backend:**

  - PHP
  - MySQL/PDO
  - Session Management

- **Security:**
  - SQL Injection Prevention
  - XSS Protection
  - Input Sanitization
  - Secure Password Hashing

## 📋 Prerequisites

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (Apache/Nginx)
- Modern web browser

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/Khadalicioso/green_tea.git
```

2. Import the database:

```bash
mysql -u username -p database_name < database/green_tea.sql
```

3. Configure database connection:

- Navigate to `components/connection.php`
- Update database credentials

4. Start your local server:

```bash
php -S localhost:8000
```

5. Access the application:

- Customer Interface: `http://localhost:8000`
- Admin Panel: `http://localhost:8000/admin`

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ and ☕
