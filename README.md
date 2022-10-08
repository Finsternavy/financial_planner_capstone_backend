# financial_planner_capstone_backend

# Important Note!  This program uses secret environmental variables that are NOT public. 

To use, you will need to create and link your own MongoDB database.  The endpoints in the project are setup to work specifically with MongoDB. 

The backend was build with Flask and MongoDB.  To run the backend you will need to install a virtual environment and dependencies listed in the requirements.txt file.
This project also requires the financial_planner_capstone_frontend available at https://github.com/Finsternavy/financial_planner_capstone_fontend

## On Windows, you can run the following commands from the root directory where you save this project:

### Add a virtual environment

python3 -m venv venv

### Activate the virtual environment

venv\Scripts\activate

***Activate the virtual environment before installing dependencies!***

### Install Flask

pip install Flask

### Install pymongo, flask-pymongo with certifi
python -m pip install pymongo flask-pymongo "pymongo[srv]" certifi

### Install CORS
pip install CORS

### Install gunicorn for production
pip install gunicorn

### Install SendGrid
pip install sendgrid


# What can it do?

### This backend has the following working functionality:
-User registration

-User login

-Account recovery email (username / password)

-Loan detail calculations (monthly payments, interest and principle breakdowns, period to payoff)

-Budget CRUD

-Debt Snowball calculations
