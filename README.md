Ecommerce Website

A full-featured e-commerce web application built with Python and Django, featuring user authentication, product browsing, cart management, and order processing.

Features
🔐 User Authentication — Sign up, log in, and manage user accounts
🛍️ Product Catalog — Browse and view products with images
🛒 Shopping Cart — Add, update, and remove items from cart
📦 Order Management — Place orders and track order history
🖼️ Media Handling — Product images and user uploads
💻 Admin Panel — Manage products, orders, and users via Django admin
Tech Stack
Backend: Python, Django
Database: SQLite
Frontend: HTML, CSS
Deployment: Render
Project Structure
mysite/
├── manage.py
├── mysite/          # Project settings, URLs, WSGI/ASGI config
├── myapp/           # Core app logic
├── cart/            # Shopping cart functionality
├── orders/          # Order processing and history
├── users/           # User authentication and profiles
└── media/           # Uploaded images and static content
Getting Started
Prerequisites
Python 3.x
pip
Installation
Clone the repository
bash
git clone https://github.com/addy-1922/Ecommerce-Website.git
cd Ecommerce-Website/mysite
Create and activate a virtual environment
bash
python -m venv env
source env/Scripts/activate   # On Windows (Git Bash)
Install dependencies
bash
pip install -r requirements.txt
Run migrations
bash
python manage.py migrate
Start the development server
bash
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser
Live Demo

🔗 Live Site (add your Render deployment link here)

Screenshots

(Add screenshots of your homepage, product page, cart, and checkout here)

Future Improvements
Payment gateway integration
Product search and filtering
Wishlist functionality
Email order confirmations
Author

Aditya Naik

GitHub: @addy-1922
License

This project is open source and available for learning purposes.
