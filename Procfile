release: python collectstatic --no-input
release: python manage.py migrate

web: gunicorn easypaisa.wsgi -b 0.0.0.0:$PORT
