# django-next
**Backend:** Django, Django Rest Framework  
**Frontend:** React, NextJs, Redux and MaterialUI  
**Dev Tools:** Docker, Docker-Compose  
**CD/CI:** TravisCI

#### Note: It is required to have `docker`, `docker-compose` on you machine.
## Build apps
To build development files:  
```
docker-compose build
```
## Run app
To run app  
```
docker-compose up
```

*Backend runs on:* `http://localhost:8000/`  
*Frontend runs on:* `http://localhost:3000/`

## Run tests
To run backend tests:  
```
docker-compose run --rm app sh -c "python manage.py test && flake8"
```
