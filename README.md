# Django User Authentication & Dashboard Application

## Description
A Django application that allows users to signup and login as either a Patient or Doctor. After login, users are redirected to their respective dashboards displaying the details entered during signup.

## Features
- User Types: Patient, Doctor
- Signup Form Fields:
  - First Name
  - Last Name
  - Profile Picture
  - Username
  - Email ID
  - Password
  - Confirm Password
  - Address (Line1, City, State, Pincode)
- Password and Confirm Password validation
- Dashboard displays user signup details

## Installation
1. Clone the repository:
   git clone <repository-url>
2. Navigate to the project folder:
   cd <project-folder>
3. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
5. Install dependencies:
   ```
   pip install -r requirements.txt
7. Apply migrations:
   ```
   python manage.py migrate
9. Create a superuser (optional):
    ```
   python manage.py createsuperuser

## Usage
1. Start the Django development server:
   python manage.py runserver
2. Open browser at http://127.0.0.1:8000
3. Signup as Patient or Doctor
4. Login with credentials
5. View the dashboard showing user info

## Notes
- Profile pictures should be in .jpg or .png format
- Password and Confirm Password must match
- Dashboard is simple and displays user signup details
