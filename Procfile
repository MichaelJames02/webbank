web: gunicorn config.wsgi:application
worker: celery worker --app=webbank.taskapp --loglevel=info
