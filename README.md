# Setup Django to Deploy on WSGI

1) Create Virtual Environment
>>python3 -m venv <name>
>>source <name>/bin/activate

2) Install Django
>> python -m pip install Django

Check Django installation
>> python -m django --version

3) Create project

>>django-admin startproject mysite

3.1) Rename to 'project_root"

4) Test the new projhect
>> cd project_root
>> python manage.py runserver