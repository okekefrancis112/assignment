# Recipe App API

A Dockerized Django REST API for managing recipes, ingredients, and tags with comprehensive test coverage and CI/CD pipeline.

## Overview

A fully tested recipe management API built with Django REST Framework, containerized with Docker, and featuring automated checks via GitHub Actions.

## Features

- **Recipe Management** — Full CRUD for recipes
- **Ingredients & Tags** — Categorize recipes with tags and ingredients
- **User Authentication** — Token-based auth
- **Docker** — Containerized development and deployment
- **CI/CD** — GitHub Actions workflow for automated testing
- **Flake8** — Code linting

## Tech Stack

- **Python** 3.x
- **Django** + **Django REST Framework**
- **Docker** + **Docker Compose**
- **PostgreSQL** (via Docker)
- **GitHub Actions** — CI/CD

## Getting Started

```bash
git clone https://github.com/okekefrancis112/assignment.git
cd assignment/recipe-app-api-main
cp .env.sample .env
docker-compose build
docker-compose up
```

### Run Tests

```bash
docker-compose run --rm app sh -c "python manage.py test"
```

## Project Structure

```
└── recipe-app-api-main/
    ├── app/
    │   ├── core/              # Core app (models, admin, management commands)
    │   ├── recipe/            # Recipe API endpoints
    │   ├── user/              # User auth endpoints
    │   └── app/               # Django settings
    ├── Dockerfile
    ├── docker-compose.yml
    └── .github/workflows/     # CI/CD config
```

## License

MIT
