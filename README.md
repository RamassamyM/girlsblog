# girlsblog
My new django (python) app

Note : for using postgresql and deployment : if use white noise :
read : https://tutorial-extensions.djangogirls.org/en/optional_postgresql_installation/
and : https://tutorial-extensions.djangogirls.org/en/heroku/
but change the config of whitenoise :
http://whitenoise.evans.io/en/stable/changelog.html#v4-0
http://whitenoise.evans.io/en/stable/django.html#django-middleware

See the deployments :
https://gigisblog.herokuapp.com/
or
http://gluglu.pythonanywhere.com
(available for 3 months if inactive)
config here : https://www.pythonanywhere.com/user/gluglu/webapps/#tab_id_gluglu_pythonanywhere_com


Before launching locally :
install dependencies in requirements.txt
version of python : see runtime.txt
django version : 2.1.1
Python : 3.7.0
use virtualenv and pip

then launch commands :
python manage.py migrate
python manage.py createsuperuser
(to create a user for admin)
