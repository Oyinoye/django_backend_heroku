# Backend for Rideco Grocery_App

API for simple grocery app done with Python and Django.

### Api Documentation
Can be seen by importing the rideco.json file into Insomnia or Postman app.
Update environment base url to port on your localhost(default: 8000)

### Setup

Create a virtual environment in the project folder using `py -m venv venv`

Activate the virtual environment with `/venv/Scripts/activate.bat`

Install all the project dependencies from the requirements file: `pip install -r requirements.txt`

Start the server:
 `py manage.py runserver`


## Other Commands

`py manage.py makemigrations` to make migrations from the models
`py manage.py migrate` to create tables in the database
`py manage.py createsuperuser` to create a super user.


### `py manage.py runserver`

Runs the app on default Django port:
Open [http://localhost:8000](http://localhost:8000).


### `py test <folder name>` to run the tests.

Sample unit testing using TestCase, basic.


### Link to Fronend:
https://github.com/Oyinoye/Grocery_App_Backend


Setup the Frontend and start using the app.


### Link to Dockerized Fullstack App source code, with PostgreSQL:
https://github.com/Oyinoye/Grocery_App_Dockerized_Fullstack



