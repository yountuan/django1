``` 
1.
makedir <dir_name>
python2 -m venv venv
touch requirements.txt
nano django, djangorestframework, psycopg2-binary, python-decouple

2.
source ./bin/activate
pip install -r requirements.txt
django-admin startproject <project_name> .

3. 
settings -> installed_apps['rest_framework']
create_db <db_name>
.env -> <key>, <db_data>
.gitignore
python3 manage.py runserver

4.
django-admin startapp <app_name>
add <app_name> to settings.installed_apps
models.py -> create class
```