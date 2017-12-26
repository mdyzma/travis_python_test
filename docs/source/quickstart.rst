.. quickstart:

Quickstart
==========


TravisCI Continuous Integration / Continuous Deployment test project. Flask application with automated code metrics, tests and Heroku deploymnet (app temporarily accessible `here <https://flask-travis-ci.herokuapp.com>`_)




# Quickstart


To deploy adpp fact follow this steps:

1. Create heroku app (web interface or HerokuCLI)::

    $ heroku create --region eu --buildpack heroku/python flask-travis-ci

2. Clone this repository::

    $ git clone https://github.com/mdyzma/travis_python_test```

3. Change Heorku API token and webapp name for your data

4. Activate repository in TravisCI