# Django-To-Do-List

A **To-Do List** app built with Django that includes user registration, login, search functionality, and complete Create, Read, Update, and Delete (CRUD) features.

## Features

- User Registration and Login
- Add, Edit, Delete tasks
- Mark tasks as completed
- Search functionality
- User-specific task management

## Prerequisites

Before you begin, make sure you have the following installed:

- Python
- Django
- Git

## Installation

Follow these steps to set up and run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/TabataRamos/to-do-list-python-django.git

```

### 2. Create and activate a virtual environment

#### On Windows:

```bash
python -m venv venv
venv\Scripts\Activate
```

#### On macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

### 4. Create migrations and apply them

Run the following commands to create and apply database migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a superuser (optional)

If you want to access the admin panel:

```bash
python manage.py createsuperuser
```

### 6. Run the server

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000` in your browser to view the application.

## Usage

1. Register for an account or log in with an existing one.
2. Create new tasks.
3. Mark tasks as completed or edit/delete them.
4. Use the search bar to find specific tasks.

## License

This project is licensed under the MIT License.
