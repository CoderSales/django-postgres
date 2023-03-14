python -m venv.venv
source .venv/Scripts/activate
pip install psycopg2
pip install Django
django-admin startproject project .
django-admin startapp app
project/settings.py INSTALLED_APPS 'app'
app/views.py