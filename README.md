<h1 align="center">
  ArgoAI
</h1>

## Info
This project is part of the CS-491 course for CS major at Rutgers University - Newark. 

## Setup
Details on how to setup the project.

### Prerequisite
- Python Version 3.9.7 ([Download](https://www.python.org/downloads/))
- Git Bash - Windows ([Download](https://git-scm.com/downloads)) 

### Environment Setup
1. Install Virtualenv `pip install virtualenv`.
2. Verify python version is 3.9.7 `python --version`.
3. Clone this repository to your desired destination `git clone https://github.com/n-man13/argoai_run.git`.
4. Check out your workspace branch `git checkout firstname-ws`.
5. Make a virutal environment `virtualenv venv`.
6. Activate the new virtual environment `source venv/bin/activate` or Windows `source venv/Scripts/activate`.
7. Install all dependencies `pip install -r requirements.txt`.

### Development Setup

#### Initial Setup
`export FLASK_ENV=main`
`export FLASK_ENV=development`
or
`set FLASK_ENV=main`
`set FLASK_ENV=development`

#### RUN Application
`flask run` and navigate to `http://127.0.0.1:5000/`

## Documentation
To get more help on the Flask go check out the [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/) or [DevDocs](https://devdocs.io/flask~2.0/)
