# Django Tutorial Project

## Overview
This project is a demonstration of my learning experience while following a Django tutorial. It covers fundamental concepts of Django, including setting up a project, handling views, templates, models, and database interactions. The goal was to gain hands-on experience in building a basic web application using Django’s robust framework.

## Features Implemented
- Django project setup and configuration
- URL routing and views handling
- Template rendering with dynamic content
- Model creation and database migrations
- Admin panel customization
- Basic CRUD operations

## Installation & Setup
To run this project locally, follow these steps:

### Prerequisites
Ensure you have the following installed on your system:
- Python (>= 3.x)
- Django (>= 4.x)
- Virtual environment (optional but recommended)

### Steps to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/rafanahmed/DjangoTutorial.git
   cd DjangoTutorial
   ```

2. Create and activate a virtual environment:
   ```sh
   python -m venv venv  # Create virtual environment
   source venv/bin/activate  # Activate (Mac/Linux)
   venv\Scripts\activate  # Activate (Windows)
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```sh
   python manage.py migrate
   ```

5. Run the development server:
   ```sh
   python manage.py runserver
   ```
   Access the application in your browser at `http://127.0.0.1:8000/`

## Key Learnings & Reflections
Through this project, I gained valuable insights into Django’s architecture and workflow, including:
- Understanding the MTV (Model-Template-View) pattern.
- Working with Django’s ORM for database management.
- Implementing URL routing and dynamic content rendering.
- Handling form submissions and user interactions.
- Exploring Django’s built-in admin interface.
