## Clone

```$ git clone https://github.com/thimyxuan/api-car-rental-price-predictor.git```

## Stack technique

- Python
- Numpy
- Pandas
- Sklearn
- Joblib
- FastAPI

## Objet

Ceci est l'API de prédiction des prix de location du projet Getaround.

Elle est déployée à l'adresse suivante : [`https://fastapi-getaround-7a9ad465e3fa.herokuapp.com/`](https://fastapi-getaround-7a9ad465e3fa.herokuapp.com/)

## Déploiement en local

Créer l'image Docker :  

```$ docker build . -t fastapi_env```

Créer le container Docker :  

```$ docker run -it -v "$(pwd):/app" -p 4000:4000 fastapi_env```

## Déploiement avec Heroku (via CLI)

Assurez-vous d'être connecté à vos comptes Docker et Heroku :    

```$ heroku login```

```$ docker login --username=<your username> --password=$(heroku auth:token) registry.heroku.com```

```$ heroku create YOUR_APP_NAME```

```$ heroku container:push web -a YOUR_APP_NAME```

```$ heroku container:release web -a YOUR_APP_NAME```

```$ heroku open -a YOUR_APP_NAME```