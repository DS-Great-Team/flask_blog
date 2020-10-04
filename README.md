## Flask-Blog
This project is the POC on **flask** the project is about how we creating a Blog using flask framework and it's libraries and modules.

## Goals
Create a POC with **Flask** and maybe later automate with Jenkins CI/CD

## Build status
No now for the moment, but we try integrate with Jenkins CI/CD and will do **TDD**

## Tech/framework used
<b>Built with</b>
- [flask](https://palletsprojects.com/p/flask/)

## Features
At beginning it is a Blog that allow: create posts, edit and delete.

## Dependencies
If you want to run into VM you must have:
* Python
* pip
* flask

Is well great on the stable versions. I tested into python 2.7 and I get a few bugs.

## Installation
If you want run into VM only do a git clone into this repo an run these commands

* Run over VM
```
$ git clone https://github.com/DS-Great-Team/flask_blog.git (for clone the repo)
$ python3.8 init_db.py (to run for first time and create the database)
$ flask run
```
If you want to run over other ports and host you maybe check this: https://stackoverflow.com/questions/20212894/how-do-i-get-flask-to-run-on-port-80

* Run over docker
```
$ git clone https://github.com/DS-Great-Team/flask_blog.git (for clone the repo)
$ python3.8 init_db.py (to run for first time and create the database)
$ docker build --tag flask:1.0 . (build the Dockerfile)
$ docker run --publish 8000:5000 --detach --name flask flask:1.0 (Run the container)
```

## API Reference
Not for now, but it will be considerer, maybe when we have a login and other apps we connected API.

## Tests
No for now, working in progress

## How to use?
If people like your project they’ll want to learn how they can use it. To do so include step by step guide to use your project.

#### Anything else that seems useful

## License
https://flask.palletsprojects.com/en/1.1.x/