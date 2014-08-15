## nastar

nastar is Web Content Management System or CMS. Based on [django](https://www.djangoproject.com/) and [django-cms](https://www.django-cms.org/en/) this project is instant django-cms for develop and deployment, using twoscoop method.


#### How To Install

Create virtualenv:

    $ virtualenv nastar
    $ source nastar/bin/activate

____________________________________________
Clone this project:

    $ git clone https://github.com/drayanaindra/nastar.git

____________________________________________
Or when you has been forking this project:

    $ git clone git@github.com:drayanaindra/nastar.git
    
____________________________________________
Install requirements:

    $ cd nastar/requirements
    $ pip install -r base.txt
    
____________________________________________
Run nastar on your local:

    $ ./manage.py syncdb --settings=nastar.settings.local
    $ ./manage.py migrate --settings=nastar.settings.local
    $ ./manage.py runserver --settings=nastar.settings.local

and open in your browser http://localhost:8000
____________________________________________

Powered : [TANGKIL Lab](http://www.tangkil.com)

Question : [@drayanaindra](https://www.twitter.com/drayanaindra)
