# Ecommerce-website-with-Django
Django-eCommerce is an open-source e-commerce platform built on the Django Web Framework.
# 💥Features Included💥
* SignUp & Login functionality.
* Edit profile functionality.
* Shopping Cart.
* Order Management.
* Increase & decrease cart items.
* Checkout functionality.
* Payments Using sslcommerz.
* Logout functionality.
# Installation
```
Download Python
https://www.python.org/downloads/

```
# Clone the Repository
After installing the prerequisite files just clone the project:<br>
```
git clone https://github.com/narayanbodade662/MILKART.git
cd MILKART/ec
```
# Create Virtual Environment
Run command in terminal:
```
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate   # On Linux/Mac

```
# Install Dependencies
```
open command prompt
pip install django
pip install pillow
pip install razorpay
```
# Run Database Migrations & Start Development Server
```
python manage.py migrate
python manage.py runserver
```
# Getting started to run the server
Run command in terminal:<br>
Execute: `python manage.py runserver`<br>
Open up a browser and visit: <span style="color: blue;">http://127.0.0.1:8000/</span> 

# 📂 Project Structure
MILKART/
│── MILKART/            # Main Django project
│   ├── app/            # Django app (models, views, urls, templates)
│   ├── static/         # CSS, JS, images
│   ├── media/          # Uploaded product images
│   ├── db.sqlite3      # Database
│   ├── manage.py       # Django management script
│── How To Run.txt      # Setup instructions

# 📸 Screenshots

## 🖼️ Project Banner
![Project Banner](ec/app/static/app/images/banner/b1.jpg)

## 🛒 Product Section
![Product Icbars](ec/app/static/app/images/product/icbars.png)  
![Curd Premium](ec/app/static/app/images/product/curd-premium.png)

# 💳 Payment Integration (Razorpay)
```
RAZORPAY_KEY_ID = "***********"
RAZORPAY_KEY_SECRET = "*********"
```
# 📜 License

This project is licensed under the MIT License.

# 👨‍💻 Developed by Narayan Bodade


