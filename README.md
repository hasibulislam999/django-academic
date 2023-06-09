# All You Need to Type as `Command` in `Terminal`

> Required commands to execute a `Django` project

## Check `Python` existence

```
python
print("Hello World!")
```

## File `Directory`

```
AcademicDjango
    |-django_env (for virtual environment)
    |   |-Scripts
    |       |-activate
    |       |-deactivate.bat
    |-preparation_project (for actual as project)
    |   |-preparation_project
    |-session_project (for actual as project)
    |   |-myapp
    |   |-myproj
    |-employee_project
    |   |-employee_project
    |   |-employee_register
```

## Create `Virtual Environment`

> Execute all tasks by enabling `virtual environment`

```
python -m venv django_env
```

### `Active` Virtual Environment

```
django_env\Scripts\activate
```

### `Deactivate` Virtual Environment

```
django_env\Scripts\deactivate.bat
```

## Install `Django`

```
pip install django
python -m django --version
```

## Create Django `First Project`

```
django-admin startproject preparation_project
cd preparation_project
```

## Run Python `Server`

```
python manage.py runserver
```

# Create `Admin`

```
python manage.py createsuperuser
```

## Default `Credentials`

- Username: `admin`
- Email: `admin@admin.com`
- Password: `admin`

### Addition `Commands`

```
python manage.py makemigrations
python manage.py migrate
```
