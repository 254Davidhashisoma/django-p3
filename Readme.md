#  Award

#### Author: [DAVID HASHISOMA](https://github.com/254Davidhashisoma)


## Description
The application will allows a user to post a project he/she has created and get it reviewed by his/her peers.

As a user of the web application you will be able to:

1. Sign up and log in
2. View post posted by other users
3. post post
4. Rate a project
5. Edit your profile
6. Generate APIs
7. Review a project

## Endpoints
You can access data from the application through the following endpoints:

1. '' to have a look at all post
2. '' to have a look at the profiles

## Setup and installations
* Clone Project to your machine
* Activate a virtual environment on terminal: `source env/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.6 manage.py runserver`
* Access the live site using the local host provided



## Getting started

### Prerequisites
* python3.6
* env environment
* pip

#### Clone the Repo and rename it to suit your needs.
```bash
git clone https://github.com/254Davidhashisoma/Django3
```
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```

#### Create and activate the virtual environment
```bash
python3.6 -m virtualenv virtual
```

```bash
source virtual/bin/activate
```

#### Setting up environment variables
Create a `.env` file and paste paste the following filling where appropriate:
```
SECRET_KEY = 'your secret key'
DEBUG=True
DB_NAME='awwards'
DB_USER='<your database name>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='*'
DISABLE_COLLECTSTATIC=1
```

#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3.6 manage.py check
python manage.py makemigrations news
python3.6 manage.py sqlmigrate news 0001
python3.6 manage.py migrate
```

#### Run the app
```bash
python3.6 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)



## Testing the Application
`python manage.py test insta`
        
## Built With

* [Python3.6](https://docs.python.org/3/)
* Django 3.1
* postgresql 
* bootstrap3 and Sematic UI
* HTML
* CSS


### License

* LICENSED UNDER  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](license/MIT)