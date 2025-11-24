
## Aplikasi Web Restoran 

## FastFoodNet – Restaurant Website Ordering System
FastFoodNet is a web-based restaurant ordering system built using PHP and MySQL. The application allows customers to browse menus, manage their cart, and complete food orders online, while providing admin functionalities to manage products, users, and transaction data.

## 📋Features
Public Frontend (Customer View)
- Landing Page displaying available menu items.
- Product Details with image, name, description, and price.
- Shopping Cart (add, remove, update items).
- Checkout & Receipt (Nota) after placing an order.
- User Authentication (Register & Login).
- Profile Management for customer accounts.

Admin Backend
- Admin Login System
- Menu Management: Add, edit, delete food items with pictures.
- Product Image Storage inside foto_produk/.
- User Profile Management
- Order & Transaction Records stored in database (trwebresto.sql).
- Cart & Checkout Processing

## 🛠 Tech Stack
- Language: PHP
- Database: MySQL
- Frontend: HTML, CSS, JavaScript

Key Directories:
- asset/ – CSS, JS, and assets
- foto_produk/ – product images
- foto_profil/ – user profile photos

## ⚙️ Prerequisites
Make sure you have installed:
- XAMPP / WAMP / MAMP / LAMP
- PHP 7.x
- MySQL
- Web browser (Chrome, Firefox, etc.)
- Code editor (VS Code recommended)

## 🚀 Installation & Setup
1. Clone the Repository

```php
git clone https://github.com/Indramustajab/Website-Restoran-FastFoodNet.git
cd Website-Restoran-FastFoodNet
```

2. Create Database
- Open phpMyAdmin
- Create a database, e.g., fastfoodnet_db
- Import the SQL file:
```php
trwebresto.sql
```

3. Configure Database Connection
Edit the koneksi.php file:
```php
$host = "localhost";
$user = "root";
$pass = "";
$db   = "fastfoodnet_db";
```

4. Run Local Server

For XAMPP users:
- Start Apache & MySQL
- Move the project folder to htdocs/
- Open in browser:
```php
[echo "Hello World!";](http://localhost/Website-Restoran-FastFoodNet/)
```

5. Authentication
- Register: register.php
- Login: login.php
Proceed to browse products, add to cart, and checkout.

## 📂 Database Schema

Main tables included in trwebresto.sql:
- users — stores login & profile information
- menu/products — item name, price, image
- orders/transactions — checkout results and receipts
- cart — temporary user items before checkout

## 🛣️ Main Pages & Routes

<table>
  <tr>
    <td><p> Page</p></td>
    <td><p> Description</p></td>
  </tr>
   <tr>
    <td><p> index.php</p></td>
    <td><p> Homepage</p></td>
  </tr>
   <tr>
    <td><p> all-menu.php</p></td>
    <td><p> List of all menu items0</p></td>
  </tr>
   <tr>
    <td><p> detail_produk.php	</p></td>
    <td><p> Product detail page</p></td>
  </tr>
   <tr>
    <td><p> cart.php</p></td>
    <td><p> Checkout process</p></td>
  </tr>
   <tr>
    <td><p> nota.php</p></td>
    <td><p> Receipt / Nota</p></td>
  </tr>
   <tr>
    <td><p> profile.php</p></td>
    <td><p> User profile</p></td>
  </tr>
  <tr>
    <td><p> login.php</p></td>
    <td><p> Login</p></td>
  </tr>
  <tr>
    <td><p> register.php</p></td>
    <td><p> Register</p></td>
  </tr>
  <tr>
    <td><p> logout.php</p></td>
    <td><p> Logout.php	</p></td>
  </tr>
    <tr>
    <td><p> protect.php</p></td>
    <td><p> Access protection script</p></td>
  </tr>
</table>

