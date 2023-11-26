# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:e orm project
creart

### STEP 2:
use django rules

### STEP 3:
end the program

Write your own steps

## PROGRAM
```
class Student (models.Model):
referencenumber=models.CharField(primary_key=True,max_length=20,help_text="reference
number") name=models.CharField(max_length=100) age=models.IntegerField()
email=models.EmailField() mobileno=models.IntegerField()
class StudentAdmin(admin.ModelAdmin): list_display=
('referencenumber','name','age','email','mobileno') from django.db import models
from django.contrib import admin
```


## OUTPUT
![output](![orm output](https://github.com/premsuryas/django-orm-app/assets/147473858/5e4e0220-a384-48a1-b575-e31598cffd6c)



## RESULT
orm was created sussesfully
