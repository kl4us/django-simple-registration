django basic project with registration, bootstrapped forms and debug toolbar included!
====================

a starter project with bootstrapped forms and user registration

Example usage
=============

    $ virtualenv mysite-env --no-site-packages
    $ source mysite-env/bin/activate
    (mysite-env)$ git clone git@github.com:kl4us/django-simple-registration.git
    (mysite-env)$ cd django-simple-registration
    (mysite-env)$ pip install -r requirements.txt
    (mysite-env)$ python manage.py syncdb
    (mysite-env)$ python manage.py runserver

Hit http://127.0.0.1:8000 to view the site!