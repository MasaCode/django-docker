# django-docker
Django development template with docker

# Project Setup 

1. Building a docker image 
```bash
$ docker-compose build
```

2. Install Django library
```bash
docker-compose run --rm app pipenv install
```

3. Create a project
```bash
$ docker-compose run --rm app pipenv run django-admin startproject [Project Nmae] .
```

4. start docker container
```bash
$ docker-compose up 
```

