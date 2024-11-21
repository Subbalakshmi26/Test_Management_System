
  Step-by-Step Installation Guide
•	cd Task-Management-System
•	pip install -r requirements.txt
•	python manage.py migrate
•	python manage.py runserver


Mastering the Task Management System
•	This is a Test Management System is a web application That allows users to manage test data
•	By using Django, We can implement features such as user authentication(login).
•	CRUD operations such as Create, Read, Update, Delete.
•	Templates for listing tests, viewing details, creating/editing forms and user login.
•	Users can filter tasks by status.
•	Users can register, log in, and have access to different features .

Table of Contents
In order to achieve all of these results, it is necessary to send the Authorization: Token with each link.
•	Authentication
o	Signup 127.0.0.1:8000/accounts/register/
o	Login 127.0.0.1:8000/accounts/login/
•	CRUD Operations
o	All Tasks 127.0.0.1:8000/me/all/
o	Create Task 127.0.0.1:8000/tasks/
o	Retrieve specific task 127.0.0.1:8000/tasks/id/ 
o	 Update Task 127.0.0.1:8000/tasks/id/
o	Delete Task 127.0.0.1:8000/tasks/id/

How to Navigate the Task Management System:
Once the system is set up, users can:
•	Register/Login: Authenticate with the system to access the task dashboard.
•	Create Tasks: Add tasks with details. 
•	Update Tasks: Modify tasks as they progress . 
•	Complete Tasks: Mark tasks as completed when done.
•	Delete Task: Unwanted tasks can be removed.






