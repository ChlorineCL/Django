# ***Django***
## **1. Environment**
### **1.1 Virtual Environment**

#### 1.1.1 virtualenv (original)
- Install: `$ pip install virtualenv`
- Create virtual environment: `$ virtualenv [env_name]`
- Activate: `$ source bin/activate`
- Deactivate: `$ deactivate`

Notation: Every time you exit and want to enter the same virtual environment, you need to `cd` into the same path which is really inconvenient.

#### 1.1.2 virtualenvwrapper (tools based on virtualenv)
- Install: `$ pip install virtualenvwrapper`
- Configure environment variables: add 2 lines at the bottom at the file `.bashrc`<br>
```
export WORKON_HOME=$HOME/.virtualenvs`<br>
source /home/lchen/anaconda3/bin/virtualenvwrapper.sh[file location]
```
- Activate modification: `$ source ~/.bashrc`
- Create virtual environment: `$ mkvirtualenv [env_name]`
- Exit current environment: `$ deactivate`
- Back to existing environment: `$ workon [env_name]`
- List exisitng environment: `$ lsvirtualenv`
- Delete virtual environment: `$ rmvirtualenv [env_name]`

## **2. Django Project**
### **2.1 Start Django Project on Localhost**
- Install: `$ pip install django==2.2.6` or `$ pip install django`
- Create project: `$ django-admin startproject [project_name]`
- `cd` into the project path
- Runserver: `$ python manage.py runserver`
- Startapp: `$ python manage.py startapp [app_name]`

### **2.2 Logical Structure**
