# django-project-template

Template to use when starting new Django 1.8 projects with PostgreSQL.

## Usage

Start a new project using this template:

```
django-admin.py startproject --template=https://github.com/jcalazan/django-project-template/archive/latest.zip --extension=py,gitignore project_name
```

Install requirements via pip:

```
pip install -r requirements.txt
```

Run database migrations:

```
python manage.py migrate
```

## Links

- Blog post explaining this setup: https://www.calazan.com/django-18-project-template/

- Took a bunch of ideas and examples from this project: https://github.com/lincolnloop/django-layout