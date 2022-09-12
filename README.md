# Cinema API
API service for cinema management written on DRF

## Installation with GitHub
Install PostgreSQL and create db

```shell
git clone https://github.com/LaskoA/cinema-api-for-deployment
cd cinema-api-for-deployment

Virtual environment install for Windows:
  - python3 -m venv venv
  - source venv/bin/activate
  - pip install -r requirements.txt
  
Virtual environment install for Mac:
  - sudo pip install virtualenv
  - virtualenv env
  - source env/bin/activate

set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db user>
set DB_PASSWORD=<your db password>
set SECRET_KEY=<your secret key> 
python manage.py runserver
```
## Run with docker
Docker should be installed

```shell
docker-compose build
docker-compose up
```

## Getting access
- create user via /api/user/register/
- get access token via /api/user/token/

## Features
- JWT authenticated
- Admin panel
- Managing orders and tickets
- Creating movies with genres and actors
- Creating cinema halls
- Adding movie sessions
- Filtering movies and movie sessions
"# cinema-api-for-deployment" 
