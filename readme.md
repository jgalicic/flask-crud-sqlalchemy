## Getting Started

# Check that Python 3 is installed
$ python3 --version

# Install pipenv
$ pip3 install pipenv

# Activate virtual environment & create Pipfile
$ pipenv shell

# Install dependencies
$ pipenv install flask flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy

# Create db.sqlite file in Python shell:
$ python3
$ >>> from app import db
$ >>> db.create_all()