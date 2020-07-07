```bash
django-admin startproject mysite

mysite/
    manage.py
    mysite/
        __init__.py
        settings.py
        urls.py
        wsgi.py
```

* `mysite` - name can change whenever
* about `manage.py` https://docs.djangoproject.com/en/2.2/ref/django-admin/
* `mysite/` use in url for import
* about `settings.py` https://docs.djangoproject.com/en/2.2/topics/settings/
* `url.py` - содержание django проекта https://docs.djangoproject.com/en/2.2/topics/http/urls/
* `wsgi.py` - https://docs.djangoproject.com/en/2.2/howto/deployment/wsgi/

```bash
cd mysite
python manage.py runserver
python manage.py runserver <port>
python manage.py runserver <IP:port>
```

Only for developing, not production. It's about Web frameworks, not Web servers.

```bash
python manage.py startapp polls

polls/
    __init__.py
    admin.py
    apps.py
    migrations/
        __init__.py
    models.py
    tests.py
    views.py
```
