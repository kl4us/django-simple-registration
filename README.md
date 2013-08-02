django basic project
====================

A starter project with bootstrapped forms, user registration and debug-toolbar included! This is not pinax, i don't like pinax because it is too much complicated for newbie django developer like me ... so, i made my own.

The project includes all required templates for:

	- login
	- registration
	- password change
	- password lost
	- account activation
	- ecc ...

Unlike pinax this project is based on django 1.5.1	

Example usage
=============

    $ virtualenv mysite-env --no-site-packages
    $ source mysite-env/bin/activate
    (mysite-env)$ pip install django==1.5.1
    (mysite-env)$ django-admin.py startproject --template=https://github.com/kl4us/django-simple-registration/zipball/master mysite
    (mysite-env)$ cd mysite
    (mysite-env)$ pip install -r requirements.txt
    (mysite-env)$ python manage.py syncdb
    (mysite-env)$ python manage.py runserver

Hit http://127.0.0.1:8000 to view the site!