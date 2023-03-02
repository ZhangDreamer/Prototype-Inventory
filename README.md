  <div align="center">
    <img src="https://github.com/ZhangDreamer/Prototype-Inventory/blob/main/media/Prototype_Inventory.png?raw=true">
</div> 

# Prototype Inventory 

Prototype Inventory is a web-based inventory system built using the Django web framework paired with a login system that separates the admin and the staffs. The system allows an admin to use the CRUD functionality on products while the staffs can make a request to order existing products.

## Installation

To use Prototype Inventory, you will need to have [Python](https://www.python.org/downloads/) and [Django](https://www.djangoproject.com/) installed on your machine. Once you have installed these prerequisites, you can follow these steps:

1. Clone this repository to your local machine.
2. Open Windows Command-Prompt or Mac Terminal
3. Navigate to the project directory.
4. Run the command `python manage.py runserver` to start the server.
5. Access the application by navigating to http://localhost:8000 in your web browser.

## Usage

To use Prototype Inventory, you will need to log in as either an admin or a staff member. The admin can use the CRUD functionality on products, while the staff can make a request to add existing products.

**To login as an admin** use username _Admin_ and password _root_

**To login as a staff** register a user by clicking on the register button on the top right of the project website and proceed to login. You can also login with an already existing user. eg. username _Mike_ and password _inventory1_

## Key Features

- Web-based inventory system with a functional register/login system.
- Separate features depending on users role **Admin** or **Staff**
- Admin users have full CRUD functionality for managing products.
- Admin users can view all staffs profile pages.
- Admin users can see additional graphs that represents the amount of products and the staff orders in the inventory.
- Staff users can make requests to order existing products to the inventory.
- User-friendly interface for easy navigation and use of the system.
- Supports multiple users

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/Django)
![PyPI - License](https://img.shields.io/pypi/l/Django)
