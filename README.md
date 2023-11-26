# Ex-04-Django-Models
# NAME:SURYAMALARV
# REFERENCE NUMBER:23013656
# Department:AIDS
# AIM:

To create django models

# DESIGN PROCEDURE

Django models

step 1:Create django project and app using the following commands django-admin startproject mymodels pytho manage.py startapp myApp

step2:create a user_profile models in model.py


![WhatsApp Image 2023-11-26 at 21 57 07_2eb2afd8](https://github.com/suryamalarv/ODD2023-WT-Ex-04-Django-Models/assets/145742486/47ed024f-6b8c-4c18-8c8b-3b606b53bb38)

add the models in the admin interface using the code admin.py


![WhatsApp Image 2023-11-26 at 21 57 05_0f53d83d](https://github.com/suryamalarv/ODD2023-WT-Ex-04-Django-Models/assets/145742486/2fa2fb86-8d64-4ef0-b5ab-76677befcaea)

write the fuction based view to render the data from the models to template in view.py


![WhatsApp Image 2023-11-26 at 21 57 08_5d8f8a54](https://github.com/suryamalarv/ODD2023-WT-Ex-04-Django-Models/assets/145742486/296aa6e6-2a13-4208-9d77-c39bf7cf4f36)

set up the url path for the templates using urls.py

![WhatsApp Image 2023-11-26 at 21 57 06_7f739eec](https://github.com/suryamalarv/ODD2023-WT-Ex-04-Django-Models/assets/145742486/54c78c65-2b04-45ba-9723-768eb1d78842)

in settings.py file add the appcreated

sept3:Now do the migrations process to initiate and save the models

python manage.py makemigrations python manage.py migrate create a template as user_profile.html
![WhatsApp Image 2023-11-26 at 21 57 09_5bdfc42f](https://github.com/suryamalarv/ODD2023-WT-Ex-04-Django-Models/assets/145742486/eccadb80-387d-4abf-b421-8da752c49248)

step4: Run the program using the following command

python manage.py runserver 8000 in the admin page you can view the models created and in the user_profile template page you can see the profile page of the user

# OUTPUT

![image](https://github.com/suryamalarv/ODD2023-WT-Ex-04-Django-Models/assets/145742486/b10c03fc-6945-43ab-ba39-de1e146e1cde)
![image](https://github.com/suryamalarv/ODD2023-WT-Ex-04-Django-Models/assets/145742486/4986e42c-f9e2-4470-954a-914a7313a065)

# RESULT:

Django model was created successfully
