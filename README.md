cookiecutter_drf ================

[![Built with Cookiecutter React Django](https://img.shields.io/badge/built%20with-Cookiecutter%20React%20Django-blue)](https://img.shields.io/badge/built%20with-Cookiecutter%20React%20Django-blue)

## How this was created

```zsh
pip install "cookiecutter>=1.7.0"
cookiecutter https://github.com/ohduran/cookiecutter-react-django
# name project cookiecutter_drf
cd cookiecutter_drf
# go to github and create cookiecutter_drf repo
git remote add origin git@github.com:durantschoon/cookiecutter_drf.git
git branch -M main
git add .
git commit -m "initial commit"
git push origin main
```

## Local setup
On your terminal, simply do `docker-compose up --build`, and wait for the containers to build. Eventually, you'll be able to see the index page by going to `[http://127.0.0.1/](http://127.0.0.1/)`.

## Test coverage
To run the tests, check your test coverage, and generate a coverage report:

```
docker-compose run --rm django pytest
```

## Deployment
You can check how to deploy your app to Heroku [here](https://github.com/ohduran/cookiecutter-react-django#deploy-to-heroku)
