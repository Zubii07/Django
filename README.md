# 🛒 EcomStore – A Basic Django E-Commerce Project

This is a beginner-friendly Django-based **E-commerce web application** developed as part of a project-based learning initiative. The project helps solidify core Django concepts such as models, admin configuration, and database setup.

---

## 📚 Topics Covered

### 1. Django Fundamentals
> **Definition:** Django is a high-level Python web framework that enables rapid development of secure and maintainable websites. It follows the **MTV (Model-Template-View)** architectural pattern.

- Installing Django
- Understanding Django’s project/app structure
- URL routing
- Views & templates

### 2. Building a Data Model
> **Definition:** Models define the structure of your database tables in Django using Python classes. They map directly to your database schema.

- Creating models in `models.py`
- Field types (CharField, IntegerField, etc.)
- Relationships (ForeignKey, ManyToManyField)
- Saving and querying model data

### 3. Setting Up the Database
> **Definition:** Django uses ORM (Object-Relational Mapping) to interact with the database. Setup involves creating migrations and applying them.

- Configuring `settings.py` with SQLite (default) or other DBs
- Running `makemigrations` and `migrate`
- Using `python manage.py shell` to test data

### 4. The Admin Site
> **Definition:** Django provides a built-in admin interface for managing application data through a web UI.

- Registering models with `admin.py`
- Customizing list displays and search fields
- Managing users and permissions

---

## 💻 Features Implemented

- Product model with attributes: name, description, price, stock
- Category model for product classification
- Admin interface to manage products and categories
- Home page listing all products
- Detail view for each product

---

## 🛠️ Technologies Used

- **Backend:** Python, Django
- **Database:** MySQL
- **Frontend:** Django templates, HTML, CSS (Bootstrap for styling)

---

## 🚀 Getting Started

### 1. Clone the repository

git clone https://github.com/Zubii07/Django.git


### 2. Create and activate virtual environment

python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate


### 3. Install dependencies

pip install -r requirements.txt


### 4. Run migrations

python manage.py makemigrations
python manage.py migrate

### 5. Create admin user

python manage.py createsuperuser


### 6. Start the server

python manage.py runserver
Visit http://127.0.0.1:8000/admin to access the admin panel.


### 📘 Short Definitions (Revision Cheatsheet)

## Model
    A Python class that defines the structure of your database table (e.g., Product, Category). Each attribute becomes a database field.

## View
    A function or class that handles incoming HTTP requests and returns HTTP responses (like HTML pages or JSON data).

## Template
    An HTML file with special Django syntax to display dynamic content using template tags like {{ variable }} and {% for %}.

## URL Dispatcher
    Maps specific URL patterns to corresponding views. Defined in urls.py using path() or re_path().

## Migration
   A version-controlled file that tells Django how to apply or undo changes to the database schema based on your models.

## Admin Site
   A built-in web interface for managing your app’s models and data. Accessed at /admin after creating a superuser.

## QuerySet
   A collection of objects retrieved from the database using Django ORM queries (like .all(), .filter(), .get()).

## ORM (Object-Relational Mapping)
   Allows you to work with databases using Python objects instead of writing raw SQL.

## Superuser
   A user account with full permissions to access and manage the Django admin panel.

## App
   A self-contained Django module that adds specific functionality. You can have multiple apps in a single project.

## Project
   The overall Django setup, containing settings, apps, and configurations.

## Shell
   Django's interactive Python console for testing queries and inspecting models. Run with python manage.py shell.

## Static Files
   Non-dynamic assets like CSS, JavaScript, and images. Placed in a static/ directory and linked in templates.

## Media Files
   Files uploaded by users (like product images). Managed through MEDIA_ROOT and served via MEDIA_URL.

## runserver
   Starts Django’s local development server. By default runs at http://127.0.0.1:8000.

## makemigrations
   Generates new migration files based on changes to your models.

## migrate
   Applies migrations to the database, syncing it with your current model definitions.

## createsuperuser
   Command-line tool to create an admin user to log into the Django admin panel.

## settings.py
   The configuration file for your Django project. Contains DB settings, installed apps, static/media paths, etc.

## manage.py
  A command-line utility to run Django commands like migrations, running the server, or opening the shell.
  

🧠 Happy Learning with Django!

