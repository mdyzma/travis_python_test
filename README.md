# travis python ci
Test repository for Travis CI/CD

[![Build Status](https://travis-ci.org/mdyzma/travis_python_test.svg?branch=master)](https://travis-ci.org/mdyzma/travis_python_test) [![codecov](https://codecov.io/gh/mdyzma/travis_python_test/branch/master/graph/badge.svg)](https://codecov.io/gh/mdyzma/travis_python_test)


# Quickstart


To deploy adpp fact follow this steps:

1. Create heroku app (web interface or HerokuCLI):

    ```$ heroku create --region eu --buildpack heroku/python flask-travis-ci```

2. Clone this repository:

    ```$ git clone https://github.com/mdyzma/travis_python_test```

3. Change Heorku API token and webapp name for your data

4. Activate repository in TravisCI