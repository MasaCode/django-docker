# django-docker
Django development template with docker

# Project Setup 

1. Building a docker image 
```bash
$ docker-compose build
```

2. Login to docker container
```bash
$ docker-compose run --rm app bash
```

2. Install Django library
```bash
docker-compose run --rm app pipenv install
```

2. Create a project
```bash
$ docker-compose run --rm app pipenv run django-admin startproject [Project Nmae] .
```

3. start docker container
```bash
$ docker-compose up 
```

