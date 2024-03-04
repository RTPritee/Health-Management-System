To use this template to start your own project:

#for env file create:
    //for windows
        #python -m venv venv
        #./venv/Scripts/activate
    //for ubuntu 
        source venv/bin/activate


#for requirement.txt install:
  #pip install -r requirements.txt 

#for migrations:
    #python manage.py makemigrations
    #python manage.py migrate

#for bootstrap module:
    #pip install django-bootstrap4