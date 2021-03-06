# My Personal Flask Boilerplate

My own Flask boilerplate for small web apps and personal projects.

Features:

- basic SQLAlchemy setup
- User model with 'name' and 'password' fields
- Flask-Httpauth and Flask-Login for authentication and authorization
- signup(). login(), logout() and get_users() views, which would work with both basic API calls and a JavaScript Client
- index.html with Bootstrap and JQuery
- stylesheet.css and site.js files with some very common features
- uwsgi
- Dockerfile
- basic Flask unittests setup
- ReadMe.md and .gitignore for GitHub
- secrets are not hidden

## Run

### Docker

Download, build an image with Docker and run on port 5000. The image is also available from my Docker Hub: ```jastr945/flask_boilerplate:v1.0```

### Traditional way

...Or create a Python virtual environment and run:
```sh
$ export FLASK_APP=app.py
$ flask initdb
$ flask run

```

## Tests
```sh
$ python -m unittest discover

```
