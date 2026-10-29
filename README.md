# Healthcare Backend

A Django REST Framework backend application for healthcare management, providing API endpoints for managing accounts, doctors, patients, and mappings.

## Tech Stack
- Python 3
- Django 6
- Django REST Framework (DRF)
- Simple JWT (Authentication)
- PostgreSQL / SQLite

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kanishk020304/healthcare_backend.git
   cd healthcare_backend
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```
