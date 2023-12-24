# DjangoRest-Docker Project

## Steps:
1. python -m venv venv
2. source venv/bin/activate
3. pip install django
4. pip install djangorestframework
5. django-admin startproject storage .
6. django-admin startapp api
7. add 'api.apps.ApiConfig' and 'rest_framework' in INSTALLED_APPS in settings.py
8. write your models
9. write the admin.py
10. python manage.py makemigrations
11. python manage.py migrate
12. python manage.py createsuperuser
13. python manage.py runserver
14. touch api/urls.py
15. touch api/serializers.py
16. add path('api/', include('api.urls')) in storage/urls.py
17. write the api/serializers.py
18. write the api/urls.py
19. write the api/views.py
20. pip freeze > requirements.txt
21. deactivate - for deactivate the virtual environment
22. create .dockerignore .gitignore, Dockerfile and docker-compose.yml in root folder

