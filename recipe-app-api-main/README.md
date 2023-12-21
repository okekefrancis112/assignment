# recipe-app-api
Recipe API project.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Testing](#testing)
- [License](#license)

## Features

- Recipe Api Service with Python and Django
- Create recipe
- List created recipes
- Download specific recipes
- Postgres database persistence using psycopg2
- ...

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python installed on your machine.
- Python env installed for project isolation.
- Postgres installed (for local database).
- Docker installed.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/okekefrancis112/assignment.git

2. Navigate to the project directory:

   cd assignment

3. Install dependencies:

   pip install -r requirements.txt

## Configuration
4. Create a .env file in the project root:

    DB_NAME=dbname
    DB_USER=rootuser
    DB_PASS=changeme
    DJANGO_SECRET_KEY=changeme
    DJANGO_ALLOWED_HOSTS=127.0.0.1

## Usage
5. To run the application, execute:

   docker-compose up --build

    The application will be accessible at http://localhost:8000.


## Testing
    To run tests, use the following command:

    python manage.py test

## License
    This project is licensed under the MIT License.
