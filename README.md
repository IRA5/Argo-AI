<h1 align="center">
  ArgoAI
</h1>

## Info
This project is part of the CS-491 course for CS major at Rutgers University - Newark. 

## Setup
Details on how to setup the project.

### Prerequisite
- Python Version 3.8.1 ([Download](https://www.python.org/ftp/python/3.8.1/))
- Git Bash - Windows ([Download](https://git-scm.com/downloads)) 

### Python 3.8.1 Downgrade
1. Get Prereq tools to build python with pip `sudo apt-get install -y make build-essential libssl-dev zlib1g-dev libreadline-dev libbz2-dev libsqlite3-dev wget curl llvm libncurses5-dev`
2. Navigate to Desktop `cd Desktop`
3. Get Python 3.8.1. tar file `sudo wget https://www.python.org/ftp/python/3.8.1/Python-3.8.1.tar.xz`
4. Extract tar file `tar xf Python-3.8.1.tar.xz`
5. Navigate to extracted folder `cd Python-3.8.1`
6. Create a make file `sudo ./configure --enable-optimizations`
7. Build and Install Python `sudo make install`

### Environment Setup
1. Verify python version is 3.8.1 `python3.8 --version`.
2. Install Virtualenv `pip install virtualenv` or `pip3 install virtualenv`.
3. Clone this repository to your desired destination `git clone https://github.com/moesaifan99/argoai_ru.git`.
4. Check out your workspace branch `git checkout "branchName"`.
5. Make a virutal environment `virtualenv -p python3.8 venv`.
6. Activate the new virtual environment (Linux) `source venv/bin/activate` or Windows `source venv/Scripts/activate`.
7. Install all dependencies `sudo pip install -r requirements.txt`.

### Script Setup
Inorder to run the scripts you will need to make it an executable.
- `chmod +x /path/to/script.sh`
- To run the script `./path/to/script.sh`

### Development Setup

#### Initial Setup
`export FLASK_APP=main`
`export FLASK_ENV=development`
or
`set FLASK_APP=main`
`set FLASK_ENV=development`

#### RUN Application
`flask run` and navigate to `http://127.0.0.1:5000/`

## Documentation
To get more help on the Flask go check out the [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/) or [DevDocs](https://devdocs.io/flask~2.0/)
