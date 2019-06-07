# Flaskr
[Official Flask Tutorial](http://flask.pocoo.org/docs/1.0/tutorial/)

## Run the application

Create the virtual environment with `python3 -m venv env`

Set environment variables:
```
export FLASK_APP=flaskr
export FLASK_ENV=development
```

Initialize the database with `flask init-db` (after setting the vars above)

Run the app with `flask run`

Or, run all in one go with:
`export FLASK_APP=flaskr && export FLASK_ENV=development && flask run`
