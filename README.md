# Creating Flask app<br/>
Fresh install instructions:<br/>
1.Install Python<br/>
2.``` $pip --version  (to check the installation) ```<br/>
3.``` $pip install virtualenvwrapper-win ( for handling virt env) or for Linux $pip install virtualenvwrapper ```<br/>

# Setting virtual environment and libs:<br/>
1..``` $mkvirtualenv someapp ( create virtual env) ```<br/>
2.``` $workon someapp ( activate created env) ```<br/>
3.``` $pip install Flask ```<br/>

# To integrate our app with PostgreSQL we need to install:<br/>
PSYCOPG2 – a Python adapter for Postgres<br/>
FLASK-SQLALCHEMY – Flask wrapper for SQLAlchemy (a powerful relational database framework that offers a high level ORM and low level access to a database’s native SQL functionality for Python.)<br/>
1.``` $pip install psycopg2 Flask-SQLAlchemy ```<br/>

# Create requirements.txt File With All Dependencies Listed<br/>
Our application must have a requirements.txt that contains all the package dependencies with the exact versions.<br/>
1.``` $pip freeze > requirements.txt. ```<br/>

#I nstall PostgreSQL 9.3 and Create Local Database<br/>
1.Disable any firewall/ network monitoring software before the installation process.<br/>
2.Download and install psql for windows or for linux<br/>
3.For windows, type sql shell and open it up.<br/>
4.Type psql and hit enter.<br/>
5.Agree to all, except the last line, entering the password you set previously in installation, after hit enter<br/>
6.Create a database user with a password - ``` $create user pandoraxcc with password 'mypassword'; ```<br/>
7.Create a database instance - ``` $create database steamapp owner pandoraxcc encoding 'utf-8'; ```<br/>

# Happy coding!
