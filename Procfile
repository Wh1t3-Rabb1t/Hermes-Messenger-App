release: python3 manage.py migrate
web: daphne livechat.asgi:application --port $PORT --bind 0.0.0.0 -v2
worker: python manage.py runworker -v2
