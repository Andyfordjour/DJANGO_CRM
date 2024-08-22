# CRM Web Application with Django
=====================================

Project Overview
This project is a Customer Relationship Management (CRM) web application built using Django. The application allows users to manage customer information through a simple and intuitive interface. It includes features like user authentication (registration, login, logout), as well as full CRUD (Create, Read, Update, Delete) operations for customer records.

Purpose
The purpose of this project is to create a functional CRM system that can be used to manage customer relationships effectively. The application is designed to be lightweight yet powerful, providing all the necessary tools for handling customer data in a secure and organized manner.

Key Features
User Authentication: Secure registration, login, and logout functionalities.
Customer Management: Full CRUD operations for managing customer records.
Responsive Design: Utilizes Bootstrap for a clean and responsive user interface.
Database Management: Configured with MySQL for storing and managing data.
Version Control: Managed through Git, with code pushed to GitHub.
Tools and Technologies
Python: Version 3.8 or higher
Django: Version 3.2 or higher
MySQL: Version 5.7 or higher
Bootstrap: Version 4.5 or higher
Git: Version control system
GitHub: For repository hosting
Installation
Prerequisites
Before you begin, ensure you have the following installed on your system:

Python 3.8+
Django 3.2+
MySQL 5.7+
Git
Installation Steps
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/crm-django.git
cd crm-django
Create and activate a virtual environment:

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Configure MySQL:

Ensure MySQL is running.
Create a database and update the DATABASES settings in settings.py with your MySQL credentials.
Apply migrations:

bash
Copy code
python manage.py migrate
Run the development server:

bash
Copy code
python manage.py runserver
Access the application:
Open your browser and navigate to http://127.0.0.1:8000/
