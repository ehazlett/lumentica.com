Lumentica
==========
This is the app for the lumentica.com site.  (Built using DjangoCMS).

Setup (using virtualenvwrapper)
---------------------------------
`mkvirtualenv lumentica`
`pip install -r requirements.txt`
`python manage.py syncdb --all`
`python manage.py migrate --fake`
`python manage.py runserver` 

This will create the virtual environment, setup the database (default is sqlite), and start a dev server on http://localhost:8000/

Templates
----------
The site uses the twitter bootstrap css framework.

The following templates are available (all templates use a global top navbar):

standard_page: Basic page (blank content)

header_2_col: Page with large marketing-style header and two columns below.

header_3_col: Page with large marketing-style header and three columns below.


