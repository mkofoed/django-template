# django-template

This is a simple template for starting a new Django project as I like it set up. A few thing to keep in mind:

- To start the project:
  - virtualenv .venv --python=python3.6
  - source .venv/bin/activate
  - pip install -r requirements.txt
  - python manage.py migrate
  - python manage.py runserver
  - Go to http://localhost:8000/
- Django Admin is at /django-admin.
- Rename /project/secrets.json.example to /project/secrets.json and change the secrets there.
- Follow this guide on DigitalOcean to set up a production environment: https://goo.gl/P3r3WM
