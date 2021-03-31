
# Instagram-clone

## Demo
https://instagram-django-clone.herokuapp.com/

### Main features

* Fully Instagram Clone

* User can post images and liked them

* Bootstrap static files included

* Use can register and login

* Separated requirements files

* SQLite by default if no env variable is set


# Getting Started

First clone the repository from Github and switch to the new directory:

    $ git clone git@github.com/Yogeshshirsath01/Instagram-clone
    $ cd {{ Instagram-clone }}
    
Activate the virtualenv for your project.
    
Install project dependencies:

    $ pip install -r requirements.txt
    
    
Then simply apply the migrations:

    $ python manage.py migrate
    

You can now run the development server:

    $ python manage.py runserver
