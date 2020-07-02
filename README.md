# listings
Django Application For Realestate listings

<pre>
  <h3>Creating basic skeleton - Windows</h3>
  1. cd C:\Users\user\Desktop\UserDjangoProject> pip install virtualenv
  2. For Create a venv run this virtualenv -p python3 venv
  3. Activate virtualenv venv\Scripts\activate
  4. It will look like this (venv) C:\Users\user\Desktop\UserDjangoProject>
  5. Then run pip install -r requirements.txt
  6. Run the django project run this./manage.py runserver
  <h4>install pylint</h4>-pip install -U pylint (in venv)
  <h4>Run Server</h4>
  -python manage.py runserver (venv)
  <h4> static command </h4>
  - python manage.py collectstatic
  <h4>Settings - static definition</h4>
  STATIC_URL = '/static/'
  STATIC_ROOT = os.path.join(BASE_DIR, 'static')
  STATICFILES_DIR = [
      os.path.join(BASE_DIR, 'sitelist/static')
  ]
</pre>
