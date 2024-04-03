# Ex02 Django ORM Web Application
## Date: 03.04.2024
## Reg no: 212222240035

## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM:
### admin.py
```
from django.contrib import admin
from .models import Employee
admin.site.register(Employee)
```
### models.py
```
from django.db import models

class Employee(models.Model):
    empid=models.IntegerField()
    empname=models.CharField(max_length=20)
    dept=models.CharField(max_length=20)
    salary=models.FloatField()
    aadhaar=models.BigIntegerField(null=True)
```

## OUTPUT

![Screenshot 2024-04-03 135704](https://github.com/Harinimuthu17/ORM/assets/130278614/e1c67395-86a6-4f55-aa94-78fbe3b33902)

![Screenshot 2024-04-03 135626](https://github.com/Harinimuthu17/ORM/assets/130278614/15d84522-7479-4498-bf41-bf323a22b389)



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
