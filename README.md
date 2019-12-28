[![](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![](https://img.shields.io/github/contributors/adityhere/Blongo.svg)](https://github.com/adityhere/Blongo/graphs/contributors)
![](https://img.shields.io/badge/python-3.5%20%7C%203.6%20%7C%203.7-blue.svg)
# Blongo 
Blongo is an open-source Blog Web-App built on the Django Web Framework 2.x with Python3

## About Blongo

#### Features
* Generation of Atom and RSS feeds
* Generation of Sitemaps

#### Dependencies
* Django
* pytz
* whitenoise

## Documentation

### Installation

##### To run Locally:
 1. Create a Python-3.x Virtual Environment [Creating Virtual Environments](https://docs.python.org/3/tutorial/venv.html#creating-virtual-environments)
 2. Install dependencies:
    `pip install -r requirements.txt`
 3. Create a `.env` file with required environment variables (Sample -> [sample.env](sample.env))
 4. Create database schema
    `python manage.py makemigrations blog`
 5. Run the migrations
    `python manage.py migrate`
 6. Create a superuser
    `python manage.py createsuperuser`
 7. Create default Blog config 
    `python manage.py initialize_blog`
 8. Run Server
    `python manage.py runserver`
