# Django CRM App

A simple Customer Relationship Management (CRM) system built with Django. This project implements basic CRUD (Create, Read, Update, Delete) operations for managing customer records.

## Features

- User authentication (register, login, logout)
- Dashboard to view all records
- Create new customer records
- View individual customer records
- Update existing customer records
- Delete customer records

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/RudraPatel25/CRM-Django-App.git
   cd crm
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```
   python manage.py migrate
   ```

5. Create a superuser (admin):
   ```
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```
   python manage.py runserver
   ```

7. Open your browser and navigate to `http://127.0.0.1:8000` to access the application.

## Usage

- Register a new user account or log in with existing credentials.
- Use the dashboard to view all customer records.
- Create new records, view details, update information, or delete records as needed.
- Access the admin panel at `http://127.0.0.1:8000/admin/` using the superuser credentials.

## License

This project is open-source and available under the [MIT License](LICENSE).
