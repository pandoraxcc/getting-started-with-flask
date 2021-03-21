# Creating Flask app
Fresh install instructions:
1.Install Python
2.``` console $pip --version  (to check the installation) ```
3.``` console $pip install virtualenvwrapper-win ( for handling virt env) or for Linux $pip install virtualenvwrapper ```

# Setting virtual environment and libs:
1..``` console $mkvirtualenv someapp ( create virtual env) ```
2.``` console $workon someapp ( activate created env) ```
3.``` console $pip install Flask ```

# To integrate our app with PostgreSQL we need to install:
PSYCOPG2 – a Python adapter for Postgres
FLASK-SQLALCHEMY – Flask wrapper for SQLAlchemy (a powerful relational database framework that offers a high level ORM and low level access to a database’s native SQL functionality for Python.)
1.``` console $pip install psycopg2 Flask-SQLAlchemy ```

# Create requirements.txt File With All Dependencies Listed
Our application must have a requirements.txt that contains all the package dependencies with the exact versions.
1.``` console $pip freeze > requirements.txt. ```

#I nstall PostgreSQL 9.3 and Create Local Database
1.Disable any firewall/ network monitoring software before the installation process. 
2.Download and install psql for windows or for linux
3.For windows, type sql shell and open it up.
4.Type psql and hit enter.
5.Agree to all, except the last line, entering the password you set previously in installation, after hit enter
6.Create a database user with a password - ``` console $create user pandoraxcc with password 'mypassword'; ```
7.Create a database instance - ``` console $create database steamapp owner pandoraxcc encoding 'utf-8'; ```

# Happy coding!
