# MongoDB + Django CRUD Application

A complete CRUD (Create, Read, Update, Delete) application built using Python, Django, Django Rest Framework (DRF), and MongoDB. This project demonstrates how to integrate Django with MongoDB and perform basic CRUD operations efficiently.

- Features

Create, Read, Update, and Delete records using Django and MongoDB.

RESTful API endpoints with Django Rest Framework.

MongoDB as the database backend for scalable and flexible data storage.

Fully functional backend with clean and modular Django structure.

- Technologies Used

Python – Programming language for backend logic.

Django – Web framework for building robust web applications.

Django Rest Framework (DRF) – For building RESTful APIs.

MongoDB – NoSQL database for storing data.

pymongo / djongo – Libraries to connect Django with MongoDB.

VS Code – Recommended IDE for development.

-Installation

- Clone the repository:

git clone https://github.com/USERNAME/MONGODB_CRUD.git


- Navigate to the project folder:

cd MONGODB_CRUD
cd student_project


- Create a virtual environment:

python -m venv .venv


- Activate the virtual environment:

# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate


Install required packages:

pip install -r requirements.txt


- Configure MongoDB connection in settings.py.

Usage

Run the development server:

python manage.py runserver


- Access the application at http://127.0.0.1:8000/

Use API endpoints to perform CRUD operations on your MongoDB database.

Project Structure

models.py – Defines MongoDB models.

views.py – Handles CRUD operations.

urls.py – API and web route mappings.

serializers.py – Converts MongoDB data to JSON and vice versa.

.venv/ – Virtual environment (ignored in Git).

- Topics Covered

Setting up Python, Django, and MongoDB.

Installing necessary packages for MongoDB integration.

Creating models and connecting MongoDB to Django.

Implementing Create, Read, Update, and Delete operations.

Handling data and interacting with MongoDB through Django.
