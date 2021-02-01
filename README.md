# PROJECT NAME
Neighbour-hood

## DESCRIPTION
A web application that allows you to be in the loop about everything happening in your neighborhood. From contact information of different handyman to meeting announcements or even alerts.

As a user of the web application you will be able to:

Sign in to the application to start using it.

Set up a profile which contains:

My name
My location
My neighborhood name
Find a list of different businesses in my neighborhood.

Find Contact Information for the emergency services

Create Posts that will be visible to everyone in my neighborhood.

Change My neighborhood when I decide to move out.

Only view details of a single neighborhood.

## Setup and installations
Fork the data onto your own personal repository.
Clone Project to your machine
Activate a virtual environment on terminal: <code> source virtual/bin/activate</code>
Install all the requirements found in requirements file.
On your terminal run <code>python3.7 manage.py runserver</code>
Access the live site using the local host provided.

## Getting started
### Prerequisites
python3.7
virtual environment
pip

### Clone the Repo and rename it to suit your needs.
<code>https://github.com/Fridah-Alwanga/Neighbour-Hood.git</code>

### Initialize git and add the remote repository
git init

git remote add origin <code>your-repository-url</code>

### Create and activate the virtual environment
python3.7 -m virtualenv virtual

<code>source virtual/bin/activate</code>

### Setting up environment variables
Create a .env file and paste paste the following filling where appropriate:

SECRET_KEY = 'glelh@7++*r%ggr(oolzal&c%hvom8ol5sep^w*h2iuqtc$0*c'

<pre><code>
DEBUG=True
DB_NAME='hood'
DB_USER='<your database name>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1

</code></pre>

## Install dependancies
Install dependancies that will create an environment for the app to run<code> pip install -r requirements.txt</code>


## Make and run migrations
<pre><code>
python3.7 manage.py check
python manage.py makemigrations news
python3.7 manage.py sqlmigrate news 0001
python3.7 manage.py migrate
</code></pre>


## Run the app
python3.7 manage.py runserver

## Built With
Python3.7
Django 2.2.8
Postgresql
Boostrap
HTML
CSS

## License
LICENSED UNDER License: MIT

