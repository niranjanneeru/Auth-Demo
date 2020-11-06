release: python drfx/manage.py makemigrations --no-input
release: python drfx/manage.py migrate --no-input

web: gunicorn drfx.drfx.wsgi