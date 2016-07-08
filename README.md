# Django and Vue.JS

This repository contains a simple example application with a backend in Django and a frontend in Vue.JS.


## Instalation

```bash
virtualenv env
source env/bin/activate
pip install -r requirements.txt
./manage.py makemigrations
./manage.py migrate

python manage.py createsuperuser
# admin / admin123
```


## Run

`./manage.py runserver`

Go to `http://127.0.0.1:8000/` and not localhost!!!

Add some data: `http://127.0.0.1:8000/admin`

