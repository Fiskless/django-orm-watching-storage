# Bank security control panel

This is an internal repository for the employees of the "Shining" bank. If you got into this repository by accident, then you will not be able to start it, because you don't have access to the database, but you can freely use the layout code or see how queries to the database are implemented.

The security control panel is a site that can be connected to a remote database with visits and pass cards of our bank employees.


### How to install

Python3 should be already installed. 
Then use `pip` (or `pip3`, if there is a conflict with Python2) to install dependencies:
```
pip install -r requirements.txt
```
You have secret data that are stored in .env-file. The example of these data is presented in example.env and presented below:
`````
HOST_NAME = your_host_name
PORT = port_number
DATABASE_NAME = database_name
USER_NAME = your_username
PASSWORD_USER = your_password
SECRET_KEY = your_secret_key	
DEBUG = debug
`````
In order to run the code you need to enter:
`````
$python manage.py runserver 127.0.0.1:8000
`````
In case of successful code execution you'll see the information in command prompt as shown below:
`````
Performing system checks...

System check identified no issues (0 silenced).
November 02, 2020 - 18:20:32
Django version 1.11.29, using settings 'project.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
`````

### Project Goals
The code is written for educational purposes on online-course for web-developers [dvmn.org](https://dvmn.org/).
