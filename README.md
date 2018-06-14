In a python3 virtualenv
1) git clone https://github.com/tejasavkhattar/StatisticalPlatform.git
2) cd StatisticalPlatform
3) git checkout develop
4) pip install -r requirements.txt
5) cd StatisticalPlatform
6) python manage.py makemigrations
7) python manage.py migrate
8) python manage.py createsuperuser
9) python manage.py runserver

API Endpoints: <br>
Signup : http://127.0.0.1:8000/api/rest-auth/registration/
<br>
Login : http://127.0.0.1:8000/api/rest-auth/login/<br>
Loged In user : http://127.0.0.1:8000/api/rest-auth/user/<br>
Logout : http://127.0.0.1:8000/api/v1/rest-auth/logout/<br>
List Of Users : http://127.0.0.1:8000/api/v1/rest-auth/users/<br>
Admin : http://127.0.0.1:8000/admin/<br>
