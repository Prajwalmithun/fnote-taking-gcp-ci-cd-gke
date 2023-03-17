# Day 1

- Creating directory structure

    1. website - (dir) for all app content

```
        website/__init__.py - for making "website" (dir) as "package"
        website/auth.py     - for login,logout,signup routes
        website/models.py   - for storing DB models
        website/views.py    - for defining URL endpoints
```

    2. main.py - (f) invoking the app 
        
- Installing flask packages

    1. flask

    2. gunicorn

    3. flask-login

    4. flask-sqlalchemy


# Day 2

- Created Nav Bar

- Created Signup page (Added security features, for username,password)

- Created Login Page

- User creation checks, flashing messages


# Day 3

- SQLAlchemy: database configuration and initialization

- Database models(schema) creation (check, models.py)

- In this project, there are 2 models(ie., 2 tables) (Note, User)

*ISSUE* [Fixed]

- Database file (sqlite file) is not getting created. [FIXED] 

**Solution**

typo with this line

app.config['SQLALCHEMY_DATABASE_URI']


# Day 4

- Created DB

- Adding users to the DB

- Adding notes to the DB

- Delete notes from DB [NOT WORKING - NEED TO FIX]


# Future Plans

- Send OTP to entered email for verification during signup

- Sign in with Google/Apple/Facebook