# Finance dashboard backend

## Dev environment

```bash
python3.10 -m venv venv
. ./venv/bin/activate
pip install -U -r requirements.txt
pip install Django
django-admin startproject backend .
pip install djangorestframework django-cors-headers==3.11.0 djangorestframework-simplejwt==5.0.0 PyJWT==2.3.0
pip freeze > requirements.txt
```

python manage.py startapp api