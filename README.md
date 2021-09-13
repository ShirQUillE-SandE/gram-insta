# Instagram
### Instagram 2.1  

## Author
Shirquille Sande

## Description
This is a simple website replication of the instagram application. A user first needs to  create an account before logging  in. 
Once you are logged in you can upload images.
Logged in users can view photos uploaded by other users in the home page of application.


## Set Up and Installations

### Prerequisites   
1. Ubuntu Software
2. Python3
3. Postgres
4. python virtual environment (virtual:venv).
5. Text editor - preferably Visual Studio Code Editor.

### Clone the  project Repo
Run the following command on the terminal:
* cd Instagram

###  Install and activate virtual environment
Activate virtual environment using python3.8 
1. Install
* python3 -m venv virtual
2. Activate
* source virtual/bin/activate

### Install dependancies
Install  all dependancies that will make the app run/function
* pip install -r requirements.txt

### Create the Database
* psql
* CREATE DATABASE instagram;


### Make Migrations
* python3 manage.py makemigrations doubletap(App name)
* python3 manage.py migrate

### Run the app
* python3 manage.py runserver
* open your browser with the local host; `127.0.0.1:8000` provided on the terminal

## Testing the application
* python3 manage.py test doubletap

## Admin dashboard
* The admin dashboard can be accessed by clicking the instagram icon.
`username: WOLLANDE`
`password: Access254`

## Technologies used
    - Python3
    - HTML
    - Django 
    - Bootstrap3
    - Heroku
    - Postgresql
    - GIT

## Enjoy :)


## Live Link

[View Live Site.] (https://graminsta2021.herokuapp.com/)

## License

Instagram2.0 clone is under the [MIT](LICENSE) license.

@shirquillesande-2021.
