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

git clone https://github.com/your-username/ecomstore.git


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

Concept | Definition
Model | Python class that defines database structure
View | Python function/class that handles HTTP requests
Template | HTML file with dynamic Django tags/variables
Migration | File that tells Django how to apply changes to the database
Admin Interface | Auto-generated backend to manage app data
URL Dispatcher | Maps URLs to views using urls.py
ORM | Object Relational Mapping – interact with DB using Python instead of SQL
QuerySet | Collection of DB queries returned by ORM


🧠 Happy Learning with Django!

