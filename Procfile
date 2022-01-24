web: gunicorn my_django_port.wsgi --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate
