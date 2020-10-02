#Lesson1 : Prepare Django Environment


## Install Virtual Environment to your PC for first time use:

```
# First install python 3.x
# Install Virual Environmnt
pip3 install virtualenv

```


## Create virtual environment for your new project environemnt "housemaid_project_env":

```
cd Projects
virtualenv housemaid_project_env
cd housemaid_project_env
source bin/activate
pip install Django
pip freeze
pip freeze >>requirments.txt
nano requirments.txt
deactivate
```


## Create source code folder for your project "hosemaid_system" and add 2 applications "housemaid, accounting":

```
cd Projects
cd housemaid_project_env
source bin/activate
mkdir src && cd src 
django-admin startproject hosemaid_system .
python manage.py startapp housemaid
python manage.py startapp accounting
ls -all
```


## Run your project:

```
cd Projects
cd housemaid_project_env
source bin/activate
cd src 
ls --all
python manage.py runserver
# open http://127.0.0.1:8000/
# close CONTROL-C

```

## Add your code to github:

```
cd Projects
cd housemaid_project_env
cd src 


```







