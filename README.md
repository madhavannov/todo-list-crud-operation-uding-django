# Django Todo List

A simple todo list application built with Django and SQLite.

## Features

- Add new tasks
- Mark tasks as complete/incomplete
- Delete tasks
- Clean web interface

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/madhavannov/todo-list-crud-operation-uding-django.git
   cd todo-list-crud-operation-uding-django
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install django
   ```

4. Run migrations:
   ```bash
   python manage.py migrate
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

6. Open your browser and go to `http://127.0.0.1:8000/`

## Usage

- Use the input field to add new tasks
- Click "Toggle" to mark tasks as complete/incomplete
- Click "Delete" to remove tasks

## Deployment

This is a basic Django application. For production deployment, consider using services like Heroku, AWS, or DigitalOcean.

## License

MIT License