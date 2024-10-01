# studybud
Discord like website...

# MongoDB - Django connection:

    python -m venv <venve_name>
    <venve_name>\Scripts\activate.bat
    pip install django
    pip install djongo
    pip install dnspython
    django-admin startproject <project_name>
    cd <project_name>
    python manage.py startapp <app_name>
    pip install pymongo==3.12.3 ( any error )
    pip install pytz
    python manage.py migrate
    python manage.py createsuperuser
    
# settings.py:

    DATABASES = {
        'default': {
            'ENGINE': 'djongo',
            'NAME': 'django',
            "CLIENT": {
                'host':
                'mongodb+srv://mokithpraneshpc:mokithpraneshpc@cluster0.yxzo6dv.mongodb.net/',
                'username': 'mokithpraneshpc',
                'password': 'mokithpraneshpc',
            }
        }
    }
