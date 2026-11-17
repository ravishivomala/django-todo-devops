# django-todo

A simple todo app built with Django.

![Todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)

### Setup

Clone the repository:

```bash
git clone https://github.com/ravishivomala/django-todo-devops.git
cd django-todo-devops
```

You need Django installed on your computer to run this app.
See the [Django installation guide](https://www.djangoproject.com/download/).

Create the database migration files if you have changed the models:

```bash
python manage.py makemigrations
```

Apply the database migrations:

```bash
python manage.py migrate
```

Create an admin user. Enter a username, password, and email when prompted:

```bash
python manage.py createsuperuser
```

Start the development server:

```bash
python manage.py runserver
```

Open http://127.0.0.1:8000/todos to use the app.

### Jenkins Automation Test

Testing Jenkins automatic build and email notifications.

Cheers and happy coding!
