Flask Heroku Sample
====================

A Hello World Python Flask example application that's ready to run on Heroku. This uses an editable git reference to specific Flask and Gunicorn commits in order to illustrate how this has to be configured to work with Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Development Setup

* `pipenv install`

* `pipenv shell`

* `python app.py`

## Deploy

* `heroku create`

* `git push heroku master`