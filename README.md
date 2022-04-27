# payment_system_django
This is a simple django payment system that uses flutterwave to accept payments from users through mobile money, cards and banks.

# Getting started
1: Clone the repo using this link

    https://github.com/Ayikanying-ux/payment_system_django.git

2: Move into the directory of the project
    cd payment_system_django

3: Create a virtual environment.
 
    virtualenv env
A virtual environment is where the projects dependencies are stored

4: Activate the environment with the command

    source env/Scripts/activate

5: Install the project dependencies 

    pip install -r requirements.txt
    
## Walkthrough

Before you interact with the application, go to `flutterwave` and create and account set up
the api keys in your django project. To make it work with this
application, use the value `http://127.0.0.1:8000/`.
