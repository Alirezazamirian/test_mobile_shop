# test_mobile_shop
an e-commerce website which was deployed on python anywhere to be shown as a test website in case of pruchasing.


Steps

1. create your venv and activate it.
2. install all the requirements.
3. create super user for admin panel to insert data.
4. run the ptoject.


# Code

## create venv
    
    python -m venv venv
    
NOTE : the second venv can be named anything as you want

## activate venv
choose your directory which your venv is located then open terminal and write the code below :

    venv/Scripts/activate

## install the requirements
change the directory where the project and req.txt file has been located then write the code below :

    pip install -r req.txt

## create super user
create the user to have an access to admin panel :

    python manage.py createsuperuser

then you will be wanted to choose the username and email and password(you can set email empty).

## run the project via the code below in terminal then on url bar set : localhost:8000/admin/

    python manage.py runserver


<h4 align="center">enjoy the project and customize it as you want <img src="https://github.com/Alirezazamirian/test_mobile_shop/blob/main/icons8-smile-24.png"><br>Do not forget to leave star<img src="https://github.com/Alirezazamirian/test_mobile_shop/blob/main/icons8-star-24.png"></h4>
