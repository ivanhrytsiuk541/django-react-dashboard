<h1 align="center">Django REST API with React BoilerPlate</h1>

## Till now Backend is ready & Frontend is integrated with django

## Authentication and Registration on frontend is Pending .. Coming soon

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Code of Conduct](https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square)](https://github.com/faisalnazik/Django-REST-Framework-React-BoilerPlate/blob/master/CODE_OF_CONDUCT.md)

### Backend

- Django REST framework for a powerful API
- Django ORM for interacting with the database
- PostgreSQL
- Unit tests with Pytest

## Features ✨

- React app Integration in the templates
- Accounts Registration and Authentication
- Config with environment variables
- Update your profile & pick an avatar

## How to Run locally 🚀

    - Install Dependencies after creating and activating virtual environement

        $ pip install -r requirements/local.txt

    - Create .env file in config and put variables for Secret Key and Database (PostgreSQL) as created in sample.env file


        $ python manage.py makemigrations
        $ python manage.py migrate

    - Install dependencies in frontend app using following commands in separate terminal
    - First make sure you have installed Node.js, I used v15.10.0 while developing this setup. For More info https://nodejs.org/en/
    - Then run following commands in dir where the package.json file is located

        $ npm install
        $ npm run dev

    - After that you should kept running this terminal as this is automatically compiling the react.js code in single file main.js
    - Then Run the following command in previous terminal to load frontend react app on django server

        $ python manage.py runserver

- React app available at `http://localhost:8000/`
- API root available at `http://localhost:8000/api/`
- Admin available at `http://localhost:8000/admin/`

![screenshot](https://github.com/faisalnazik/Django-REST-Framework-React-BoilerPlate/blob/master/REST-API-DOCS.png)

## ⭐️ Support

Give a ⭐️ if this project helped you!

## License ©

[The MIT License](LICENSE)
