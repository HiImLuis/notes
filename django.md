# Luis's developer notes

## Django
**Official page:** (https://www.djangoproject.com/)

### What's Django?
Django is a python based web framework to build client-server side applications

### Installing tools

### Python

- Install python
> sudo apt install python3

### Virtualenv
- Install virtualenv (optional)
> sudo apt install virtualenv

- Create a virtual environment
> virtualenv environment\_name

- Create a python3 virtual environment (if you have python 2 or more than 1 python 3 installations)
> virtualenv -p python3 environment\_name

- Activate virtual envirnoment
> virtualenv\_name/bin/activate

### Django
- Install Django
> pip install django

#### Extra packages
> pip install djangorestframework
> pip install pillow
> pip install reportlab
> pip install django-extensions

### Database (MariaDB)
- Install database server
> sudo apt install mariadb-server

#### Configuration
> sudo mysql\_secure\_installation
**Create a user for me and for development**
> > CREATE USER 'username' IDENTIFIED BY 'password\_here';
> > GRANT ALL PRIVILEGES ON \*.\* TO 'username';
or just\
> > GRANT CREATE, UPDATE, DELETE ON database\_name.table\_name TO 'username';
granted permissions will be defined by you\

### Conecting Django with MariaDB

#### Packages needed
- python3-dev
> pip install python3-dev

- libmariadbclient.dev



### Start a Django project

**python manage.py 


