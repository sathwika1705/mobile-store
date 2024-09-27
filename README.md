# Online Mobile Store Management System

## Features

### Admin Panel
- Secure Login/Logout
- Dashboard Page
- Manage Brand List
- Manage Product Category List
- Manage Product Sub Category List
- Manage Product List
- Manage Stock Availability and Pricing (Inventory)
- List all placed Orders
- View Order Details
- Update Order Status
- Manage System Information
- Upload Banner Images
- Manage Account Credentials

### Public/Client-Side
- Secure Login and Registration
- Home Page
- Explore Products
- Display Store Banner Images
- Filter Products by selected/checked brands (Home Page)
- List Product by Categories
- List Product by Sub Categories
- View Product
- Display Related Product (Below Product View Page)
- Add Product to Shopping Cart
- Manage Cart
- Empty Shopping Cart
- Checkout Shopping Cart
- Place Order
- Place Order and Pay using PayPal
- List All Orders
- View Order Details
- Manage Account Credentials

## System Snapshots
- Public/Client-Side Home Page
- Product View Page
- Admin Panel Dashboard Page
- Admin Panel Product List
- Admin Panel Inventory Page
- Admin Panel View Order Details Page

## How to Run

### Requirements
1. Download and Install any local web server such as XAMPP/WAMP.
2. Download the provided source code zip file.

### Installation/Setup
1. Open your XAMPP/WAMP's `php.ini` file and uncomment the GD Library.
2. Open your XAMPP/WAMP's Control Panel and start Apache and MySQL.
3. Extract the downloaded source code zip file.
4. If you are using XAMPP, copy the extracted source code folder and paste it into the XAMPP's `htdocs` directory. 
   If you are using WAMP, paste it into the `www` directory.
5. Browse the PHPMyAdmin in a browser: `http://localhost/phpmyadmin`.
6. Create a new database named `mobile_store_db`.
7. Import the provided SQL file (`mobile_store_db.sql`) located inside the database folder.
8. Browse the Online Mobile Store Management System in a browser:
   - Public/Client-Side: `http://localhost/mobile_store/`
   - Admin Panel: `http://localhost/mobile_store/admin`

### Default Admin Access Information
- **Username:** admin
- **Password:** admin123

