release: python manage.py migrate
web: gunicorn prj_portfolio.wsgi --log-fil -
web: gunicorn prj_portfolio:app --preload
web: gunicorn prj_portfolio:app