web: gunicorn config.wsgi:application
worker: celery worker --app=2scoops.taskapp --loglevel=info
