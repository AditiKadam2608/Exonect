
# Inventory Management System

## Description
A backend system for managing inventory with features like CRUD operations, JWT authentication, Redis caching, and background tasks using Celery.

## Setup
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Setup PostgreSQL database and update settings.
4. Run migrations: `python manage.py migrate`
5. Start Redis server.
6. Start Celery worker: `celery -A project_name worker --loglevel=info`
7. Run the Django server: `python manage.py runserver`
