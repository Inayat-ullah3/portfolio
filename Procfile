web: cd tecsec && python manage.py migrate && python manage.py collectstatic --noinput && gunicorn tecsec.wsgi:application --bind 0.0.0.0:$PORT
