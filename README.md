# ecommerce_wesbsite
An eCommerce website built with HTML, CSS, PHP, and MySQL, featuring user login, product catalog, shopping cart, and order management.

A dynamic eCommerce website built using HTML, CSS, PHP, and MySQL. It includes both user-facing and admin-facing functionalities, allowing users to register, log in, browse products, add items to cart, and place orders. Admins can manage products through a secure dashboard.

## 🛠 Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL
- **Authentication**: PHP sessions & bcrypt hashing

## 📦 Features

### 🧑‍💻 User Features
- User registration and login
- Secure password storage using bcrypt (`generate_hash.php`)
- Browse products on the homepage
- Add items to cart
- View cart and proceed to checkout

### 🔐 Admin Features
- Admin login and dashboard
- Add, edit, and manage products
- View customer orders


## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ecommerce.git
2. Import the Database
Import the SQL file (if available) into your MySQL database.

Configure your DB credentials in includes/db.php.

3. Run Locally
Use XAMPP/WAMP

Place the ecommerce folder in htdocs

Visit: http://localhost/ecommerce
```
📂 Project Structure

ecommerce/
├── admin/
│   ├── add_product.php
│   ├── dashboard.php
│   ├── generate_hash.php       # Bcrypt password generator
│   ├── login.php
│   ├── logout.php
│   └── manage_product.php
├── css/
│   └── styles.css
├── images/
├── includes/
│   └── db.php                  # MySQL database connection
├── pages/
│   ├── cart.php
│   ├── login.php
│   ├── logout.php
│   └── register.php
├── index.php                   # Homepage
├── test_db.php                 # Database test file
├── README.md
└── .gitignore

