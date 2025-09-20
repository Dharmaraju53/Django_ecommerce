Django E-commerce Application

Django E-commerce is a fully-featured e-commerce platform built with Django. This application allows users to browse products, manage shopping carts, place orders, and provides an admin interface to manage products, categories, and orders. It is designed to be easy to set up and extend for personal or commercial projects.

Features

User registration and authentication

Product catalog with categories and search functionality

Shopping cart and checkout system

Order management

Admin dashboard for managing products, categories, and orders

Responsive design for desktop and mobile devices

Installation

Follow these steps to set up the project locally:

1. Clone the repository
git clone https://github.com/Dharmaraju53/Django_ecommerce.git
cd Django_ecommerce

2. Create and activate a virtual environment
# Create virtual environment
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

4. Run database migrations
python manage.py migrate

5. Create a superuser (admin account)
python manage.py createsuperuser

6. Start the development server
python manage.py runserver

7. Access the application

Frontend: http://127.0.0.1:8000/

Admin interface: http://127.0.0.1:8000/admin/
 (login with your superuser credentials)

Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve this project.