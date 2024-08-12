# Convin-Assignment
Assignment: Daily Expenses Sharing Application

 # Prerequisites
 ## Python 3.x
 ## Django

# Setup Django:
  ## Make sure MongoDB is installed and running. Adjust the database settings in settings.py as needed:
   ```
  DATABASES = {
    'default': {
        'ENGINE': 'djongo',
        'NAME': 'expenses_db',
    }
    }
  ```


# Apply the migrations:

```
python manage.py makemigrations
python manage.py migrate
```

# Run the server:

```
python manage.py runserver
```

# API Endpoints

## Create User: POST /api/users/
### you can see the testing of api on postman in below image
![image](https://github.com/user-attachments/assets/3adb5954-7dc0-401a-96dc-90e087ec1f71)


## Retrieve User Details: GET /api/users/{id}/
### you can see the testing of api on postman in below image
![image](https://github.com/user-attachments/assets/70af4d4b-8e11-4792-bcf3-4f88198943d3)

## Add Expense: POST /api/expenses/
### you can see the testing of api on postman in below image -> it is a post request so user have to provide data 
![image](https://github.com/user-attachments/assets/fecc4d1d-4796-45c6-ba64-c1024ab8fb5f)

## Retrieve Individual User Expenses : /api/expenses/{enter user id}/user_expenses/
### you can see the testing of api on postman in below image
![image](https://github.com/user-attachments/assets/6f2b58a0-0096-4153-bccc-7e29068de7db)

## Retrieve Overall Expenses : /api/expenses/all_expenses/
### you can see the testing of api on postman in below image
![image](https://github.com/user-attachments/assets/be1a678a-3eb9-4e9b-a89e-78f25e156469)
