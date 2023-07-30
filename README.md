# Little-Lemon-Web-Application

to run the app you should set a mysql database on settings.py or use bellow database settings:
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'reservations',
        'HOST' : '127.0.0.1',
        'PORT' : '3306',
        'USER' : 'admindjango',
        'PASSWORD' : 'empye!e@123',
    }
}

the web app urls:
    /about/
    /book/
    /reservations/
    /menu/
    /menu_item/<int:pk>/
    /bookings/
