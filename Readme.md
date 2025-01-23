Required packages : 
..................................................................................
# Step 1 - install and activate virtualenvironment: 
1. pip install virtualenv
2. virtualenv env
3. env/Scripts/activate

# Step 2 : install packages
1. pip install flask
2. pip install flask-sqlalchemy
3. pip install flask_ngrok
4. pip install nltk

# Step 3 : create database
1. flask shell
2. from app import db
3. db.create_all()

