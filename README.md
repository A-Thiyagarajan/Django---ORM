# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

## DESIGN STEPS

### Step-1: Clone the repository in GitHub
$ git clone https://github.com/sec/repo.git

### Step-2: Change directory to the name of the repository cloned.
$ cd repo

### Step-3: Change directory to the sub-folder
$ cd dataproject

### Step-4: Create a new app
$ python3 manage.py startapp myapp

### Step-6: Click on settings.py and insert “import os”. Then insert ‘myapp’ in the configuration INSTALLED_APPS

### Step-7: Check whether Django server is installed successfully
$ python3 manage.py runserver 0:8000
Go to the URL ‘http://sec.student.saveetha.in:8000/’

### Step-8:  Inform Git that you want to include updates to a particular file in the next commit. 
$ git add -A

### Step-9: Configure GitHub username
$ git config user.name "sec"

### Step-10: Configure GitHub email
$ git config user.email "sec@gmail.com"

### Step-11: Commit all the updates
$ git commit -m "Success"

### Step-12: Change the URL of the GitHub remote repository
$ git remote set-url origin https://sec:TOKEN@github.com/sec/repo.git

### Step-13: Push the changes in the branch to the Github repository
$ git push origin main

### Step-14: Create a migration file that contains code for the database schema of a model
$ python3 manage.py makemigrations

### Step-15: Apply all the migrations to the database
$ python3 manage.py migrate

### Step-16: Create admin
$ python3 manage.py createsuperuser

Username: admin
Email address: admin@gmail.com
Password: 
Password (again): 
Superuser created successfully.

### Step-17: Run Django admin
	$ python3 manage.py runserver 0:8000

### Step-18: Copy the program in README.md and add the screenshot of output

### Step-19: Inform Git that you want to include updates to a particular file in the next commit. 
$ git add -A

### Step-20: Push the updated file to GitHub
	$ git push http://sec:TOKEN@github.com/sec/repo.git


## PROGRAM


## OUTPUT

Include the screenshot of your admin page.


## RESULT
