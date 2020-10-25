Simple Flask Todo App using SQLAlchemy and SQLite database.

For styling [semantic-ui](https://semantic-ui.com/) is used.

### Setup
Create project with virtual environment

```console
$ mkdir myproject
$ cd myproject
$ python3 -m venv venv
```

Activate it
```console
$ source venv/bin/activate
```

Install Flask
```console
$ pip install Flask
$ pip install Flask-SQLAlchemy
```

Set envoronment variables in terminal
```console
$ export FLASK_APP=app.py
$ export FLASK_ENV=development
```

Run the app
```console
$ flask run
```

OR

```console
$ python app.py
```