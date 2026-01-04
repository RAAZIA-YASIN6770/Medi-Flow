# MediFlow

MediFlow is a Django-based web application designed to streamline medical workflows.

## Tech Stack
- **Python**: 3.14
- **Django**: 5.2.7
- **Database**: SQLite (Default)

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### 1. Setup
Navigate to the project directory:
```bash
cd MediFlow
```

### 2. Install Requirements
Ensure Django is installed (or install from requirements if available):
```bash
pip install django
```

### 3. Database Migration
Initialize the database tables:
```bash
python manage.py migrate
```

### 4. Create Admin User
To access the admin panel, create a superuser:
```bash
python manage.py createsuperuser
```

### 5. Run Server
Start the development server:
```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/admin/` to log in.
