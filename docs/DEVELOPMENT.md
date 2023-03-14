python -m venv.venv
source .venv/Scripts/activate
pip install Django
django-admin startproject project
cd project
python manage.py runserver
python manage.py startapp app