## Python-Newsfeed

Deployed Application: https://python-newsfeed-23.herokuapp.com/

## Description

Python Newsfeed is a refactor of an existing newsfeed application to use Python for the backend. The application allows users to sign up, create, edit, and delete posts, comment on posts, and upvote posts. The homepage for Python Newsfeed is shown below:

![python-newsfeed-hp](https://user-images.githubusercontent.com/108894754/222511902-9a0f9245-500a-49cf-a17d-12ce96fd15bb.png)

Python Newsfeed uses a MySQL database and the SQLAlchemy ORM to create db tables. The app uses Flask for CRUD operations (Create, Read, Update, Delete) and API routes. It uses Jinja for rendering templates on the server side, populating the templates with data from the database. Python Newsfeed uses bcrypt for hashing users passwords. It also uses custom Python decorators to conditionally render parts of the application based on whether or not users are logged in.
Python Newsfeed is deployed through Heroku and uses Gunicorn as the web server.

* [Instillation](#instillation)
* [Usage](#usage)
* [Plans for Future Development](#plans-for-future-development)
* [Dependencies](#dependencies)
* [License](#license)
* [Tests](#tests)
* [Contact](#contact)

## Instillation

If users would like to install Python Newsfeed on their local machines, they will need to install python by downloading it here:

https://www.python.org/downloads/

They will need to set up a virtual enviornment using the command line to install dependencies using the following commands:

python -m venv venv
.\venv\Scripts\activate

The dependencies for this application, such as Flask, are listed in the "Dependencies" section below.

## Usage

The first thing users will need to do when using Python Newsfeed is signup. When they return to the site they will need to login:

![python-newsfeed-login](https://user-images.githubusercontent.com/108894754/222518104-ec3789aa-e28a-4f20-82a1-b92998e368ea.png)

When users login, they will be taken to their dashboard where they can create posts and see their previous posts:

![python-newsfeed-dash](https://user-images.githubusercontent.com/108894754/222518356-11c32fe6-d4aa-4bea-b89d-37d3ffbe4c7b.png)

Users can click "Edit Post" and the app will take them to the following screen where they can edit a post's title or delete it:

![python-newsfeed-edit](https://user-images.githubusercontent.com/108894754/222518899-7e0e8736-e92f-4fd3-acf4-9d14af5211ff.png)

From the homepage, users can click on other users' posts and comment on them:

![python-newsfeed-comment](https://user-images.githubusercontent.com/108894754/222519186-059696ef-a0f7-4fb8-963b-389ddd9a4d29.png)

## Plans for Future Development

In the future, I would like to improve upon the front end of this application. The primary purpose was to learn how to create a backend using Python, but the frontend experience for the user can be vastly improved.

## Dependencies

The application's primary dependencies are:
bcrypt
Flask
Gunicorn
Jinja2
PyMySql
Python-dotenv
SQLAlchemy

## Licenses

There are currently no licenses for this application.

## Tests

There are currently no tests for this application.

## Contact

Email: patrickmacdonald07@gmail.com
GitHub: https://github.com/pmacdonald07
LinkedIn: https://www.linkedin.com/in/patrick-macdonald-nc/