# Blog Project

A Django-based blog application where users can create, read, edit, like, dislike, and comment on blog posts.

## Features

* User authentication
* Read blog posts
* Search blog posts
* Create and publish blog posts
* Edit blog posts
* Like and dislike blog posts
* Comment on blog posts
* User profile management
* Upload profile pictures
* Change password and profile information

## Technologies Used

* **Django** — Web framework
* **Bootstrap** — Frontend styling and responsive UI
* **Font Awesome** — Icons
* **Django Crispy Forms** — Form rendering and styling
* **SQLite** — Database

## Project Structure

```text
blog_project_django/
├── .gitignore
├── manage.py
├── README.md
├── requirements.txt
├── db.sqlite3
│
├── media/
│   ├── blog_images/
│   └── profile_pics/
│
├── static/
│
├── templates/
│   ├── base.html
│   │
│   ├── App_Blog/
│   │   ├── blog_details.html
│   │   ├── blog_list.html
│   │   ├── create_blog.html
│   │   ├── edit_blog.html
│   │   └── my_blogs.html
│   │
│   └── App_Login/
│       ├── add_pro_pic.html
│       ├── change_pass.html
│       ├── change_profile.html
│       ├── login.html
│       ├── profile.html
│       └── signup.html
│
├── App_Blog/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   │
│   ├── migrations/
│   │   ├── __init__.py
│   │   └── 0001_initial.py
│   │
│   └── templatetags/
│       ├── __init__.py
│       └── custom_filters.py
│
├── App_Login/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   │
│   └── migrations/
│       ├── __init__.py
│       └── 0001_initial.py
│
└── blog_project_django/
    ├── __init__.py
    ├── asgi.py
    ├── settings.py
    ├── urls.py
    ├── views.py
    └── wsgi.py
```

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone <your-repository-url>
cd blog_project_django
```

Create and activate a virtual environment:

```bash
python -m venv env
```

On Windows:

```bash
env\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Apply database migrations:

```bash
python manage.py migrate
```

Start the development server:

```bash
python manage.py runserver
```

The application will then be available at:

```text
http://127.0.0.1:8000/
```

## Author

**Rezaul Karim Rifat**

GitHub: [@rezasdsju](https://github.com/rezasdsju)
