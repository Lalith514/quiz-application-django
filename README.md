# quiz-application-django

Installing dependencies
It will install all required dependies in the project.
pip install -r requirements.txt

Migrations
To run migrations.
python manage.py makemigrations
python manage.py migrate

Create superuser
To create super user run.
python manage.py createsuperuser
After running this command it will ask for username, password. You can access admin panel from localhost:8000/admin/

Running locally


To run at localhost. It will run on port 8000 by default.
python manage.py runserver.
