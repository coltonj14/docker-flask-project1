# Project Setup

[![Production Workflow](https://github.com/coltonj14/docker-flask-project1/actions/workflows/prod.yml/badge.svg)](https://github.com/coltonj14/docker-flask-project1/actions/workflows/prod.yml)

* [Production Deployment](https://cj236-project1-production.herokuapp.com/)


[![Development Workflow](https://github.com/coltonj14/docker-flask-project1/actions/workflows/dev.yml/badge.svg)](https://github.com/coltonj14/docker-flask-project1/actions/workflows/dev.yml)

* [Developmental Deployment](https://cj236-project1-development.herokuapp.com/)

## Project 1+2 
Colton Johnson

## Running Locally

1. To Build with docker compose:
   docker compose up --build
2. To run tests, Lint, and Coverage report use this command: pytest --pylint --cov

.pylintrc is the config for pylint, .coveragerc is the config for coverage and setup.py is a config file for pytest


### Future Notes and Resources
* https://flask-user.readthedocs.io/en/latest/basic_app.html
* https://hackersandslackers.com/flask-application-factory/
* https://suryasankar.medium.com/a-basic-app-factory-pattern-for-production-ready-websites-using-flask-and-sqlalchemy-dbb891cdf69f
