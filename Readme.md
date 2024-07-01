Coffee Shop Management System
The Coffee Shop Management System is a Django-based web application designed to streamline operations within a coffee shop environment. It provides features for user authentication, employee roles, order management, and administrative functionalities.

Features
User Authentication

Employees and managers can securely log in to the system.
Employee Roles

Employees: Can take orders from customers.
Managers: Can add or remove employees, and view all orders.
Order Management

Employees can create new orders, update existing orders, and view order history.
Each order includes customer details, items ordered, and total price.
Admin Panel

Managers have access to administrative functionalities:
Add, edit, or remove employees.
View all orders placed.

Installation and Setup
Follow these steps to set up the Coffee Shop Management System locally:

Clone the Repository

bash
Copy code
git clone https://github.com/your_username/coffee-shop-management.git
cd coffee-shop-management
Create a Virtual Environment

bash
Copy code
python -m venv venv
Activate the Virtual Environment

On Windows:
bash
Copy code
venv\Scripts\activate
On macOS/Linux:
bash
Copy code
source venv/bin/activate
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Run Migrations

bash
Copy code
python manage.py migrate
Create a Superuser (Manager Access)

bash
Copy code
python manage.py createsuperuser
Start the Development Server

bash
Copy code
python manage.py runserver
Access the Application

Open a web browser and go to http://127.0.0.1:8000/ to view the Coffee Shop Management System.