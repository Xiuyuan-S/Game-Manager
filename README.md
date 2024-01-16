# Game-Manager
It's a full-stack application allows user to manage the game they bought.

# Instructions: 
## Before you begin, ensure you have the following installed:

* Python 3
* Node.js and npm
* MySQL (Make sure you hit the lighting button in MySQL to create all tables and double-check it in schema)

## Backend Set up:
1. Install Python dependencies:
   Open your terminal and run the following commands to install the required Python packages:
   ``` 
    pip install Flask
    pip install Flask-SQLAlchemy
    pip install mysql-connector-python
    pip install flask-cors
    pip install werkzeug
    pip install flask-cors
   ```
3. Install react dependencies:
   npm install axios
   npm install react-router-dom
   npm install bootstrap
4. Connect to database: In app.py line 10 make sure to switch and to your own username and password:
   app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+mysqlconnector://username:password@localhost:3306/gamedatabase'

5. Run server&application:
   ### Run backend server:
   python -m flask run
   ### Run react app:
   npm start
   

## UML of the application:
![UML](https://github.com/Xiuyuan-S/Game-Manager/assets/88308061/76c16186-be07-43bd-980f-59348836d3b6)

## User flow:
![User flow](https://github.com/Xiuyuan-S/Game-Manager/assets/88308061/1ab54943-dbe3-42d8-baf8-5db81e2e88c1)
