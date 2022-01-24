web: gunicorn my_django_port.wsgi --log-file - 
python manage.py collectstatic --noinput
manage.py migrate
