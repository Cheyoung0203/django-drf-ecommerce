# Packages

django
python-dotenv 0.21.1
djangorestframework==3.14.1
pytest==7.2.0
pytest-django-4.5.2

# Commands

django-admin startproject drfcommerce

./manage.py runserver

<!-- 파이썬 쉘에서 -->
from django.core.management.utils import get_random_secret_key

print(get_random_secret_key())
<!-- local, production 마다 비밀키를 다르게 사용하자! -->

python -m pip install --upgrade pip

pip install python-dotenv

pip install pytest

pip install pytest-django

## Pytest

pytest -h # prints options _and_ config file settings

