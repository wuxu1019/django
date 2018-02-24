# django
Home Django Enviroment (MAC)

#########################

CREATE A VIRTUAL ENVIRONMENT

1) Install virtual environment using pip install virtualenv.
2) Navigate to the project folder and type virtualenv env 
   (Here env is the name of the virtual environment). 
   This will create a new folder named env inside the project folder.
3) Navigate to env/Scripts inside your Project Folder using cd env/Scripts.
4) Type activate and press Enter. 
   This should start the virtual environment. 
   You can verify this as (env) would be prefixed to your current path.

INSTALL DJANGO

1) Once inside the virtual environment, 
   head back to your project folder using cd ../.. and type pip install django
2) You can verify its installation by typing django-admin --version. 
   It should display the django version number installed inside the virtual environment.

Now type python manage.py runserver to start the python server.
