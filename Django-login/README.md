# Django login APP
This web app has been developed using the popular Django framework and Bootstrap for the frontend. This app can be integrated into a project that needs to have a registration and login system.

### Basic Features
    
* Register – Users can register and create a new profile
* Login - Registered users can login using username and password
* Social Apps Login – Users can login using their GitHub or Google account
* User Profile - Once logged in, users can create and update additional information such as avatar and bio in the profile page
* Update Profile – Users can update their information such as username, email, password, avatar and bio
* Remember me – Cookie Option, users don’t have to provide credentials every time they hit the site
* Forgot Password – Users can easily retrieve their password if they forget it 
* Admin Panel – admin can CRUD users


### Quick Start
To get this project up and running locally on your computer follow the following steps.
1. git clone the repository
2. Run the following commands
```
$ conda env create -f environment.yaml
$ conda activate django_login
$ python manage.py migrate
$ python manage.py createsuperuser
$ python manage.py runserver
```
   
3. Open a browser and go to http://localhost:8000/
