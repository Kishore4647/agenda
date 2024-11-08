# agenda
This is a simple, responsive To-Do List web application built with Django and styled with Django Crispy Forms. The app allows users to create, view, update, and delete tasks, with an intuitive and clean interface.
Features
Task Management: Create, update, delete, and mark tasks as complete.
User Authentication: Secure user registration and login to manage personal tasks.
Responsive UI: Mobile-friendly design thanks to Django Crispy Forms.
Task Filtering: Filter tasks by status (e.g., pending, completed).
Tech Stack
Backend: Django
Frontend: Django Crispy Forms for responsive forms.
Database: Default SQLite (easily configurable to other databases)
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
Python 3.8+
Django 3.2+
Django Crispy Forms
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/kishore4647/agenda.git
cd agenda
Set up a virtual environment (recommended):

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # For Linux/MacOS
venv\Scripts\activate  # For Windows
Install dependencies:

bash
Copy code
Set up the database:

bash
Copy code
python manage.py migrate
Create a superuser for accessing the admin panel:

bash
Copy code
python manage.py createsuperuser
Run the development server:

bash
Copy code
python manage.py runserver
Access the app: Visit http://127.0.0.1:8000 to access the To-Do List app.

Usage
Register/Login: Create an account or log in to access your to-do list.
Create Tasks: Add new tasks with a title and optional description.
Edit/Delete Tasks: Update task details or remove tasks as needed.
Mark as Complete: Mark tasks as complete or revert them to incomplete.

Contributing
Contributions are welcome! Please open an issue to discuss what you would like to change or add.
