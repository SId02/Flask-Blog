**Python Flask Demo**




Blog using Flask with database sqlite3

**Steps to create Flask project :**

- Create a folder with name Flask-log
- Create Virtual Enviroment using python -m venev venv [2nd venv is the name of virtual 	   		enviroment name can be any]
- Then install flask using pip install flask
- Create templates and Static folder for template and static file
- Install SQLAlchemy using pip install Flask-SQLAlchemy

`form aapp import db
db.create_all()
from app import BlogPost
BlogPost.query.all()
db.session.add(BlogPost(title='Blog post 1',content='Blog post1 content',author='unknown'))`



- Flask Documentation : https://flask.palletsprojects.com/en/1.1.x/
- jinja2 Template : https://jinja.palletsprojects.com/en/2.11.x/intro/#installation
