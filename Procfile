web: daphne cfehome.asgi:application --port $PORT --bind 0.0.0.0
worker: python manage.py runworker channel_layer -v2
web: gunicorn cfehome.wsgi --log-file -
