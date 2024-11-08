# Django To-Do List Application

A simple web-based To-Do List application built using Django. This project allows users to create, view, update, and delete tasks.

## Features

- Add new tasks with titles and descriptions
- View a list of all tasks
- Mark tasks as completed
- Update task details
- Delete tasks

## Prerequisites

- Python 3.10
- Django 5.1.2 (or compatible version)
- Virtualenv (optional but recommended)

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/django-todo-list.git
   cd django-todo-list

2. **Create and Activate a Virtual Environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install Required Packages**

    ```bash
    pip install -r requirements.txt

4. **Run Migrations**

    ```bash
    python manage.py migrate

5. **Run the Development Server**

    ```bash
    python manage.py runserver
    
Open your browser and go to http://127.0.0.1:8000 to see the To-Do List application in action.