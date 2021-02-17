# Django-Rest-Framework-API
Designed REST APIs using Django REST Framework
Models:
1. Designed the User Model with username(unique field), email(unique field), first_name,
last_name,m password. (You can use the django inbuilt user model)
2. Designed A Step Model with step_text(string field, not null), Many to One relationship with
Recipe
3. Designed An Ingredient Model with text(not null, string), Many to One relationship with
Recipe
4. Designed A Recipe Model with name(string, not null), Foreign Key to User table(one to one
relationship), One to Many relationship with Step and Ingredient Model
API:
Created API’s to create a new recipe, get recipes by particular user, get all the
recipes , update a recipe, delete a particular recipe
