# Interview-Site

Assuming python and django are currently installed on the machine.

Navigate to the directory of a django project  and activate an instance of django or you could install the IntProj directory I included or use your own. 

Run the following 
>>>IntProj\Scripts\activate.bat

Exit that directory and enter the top interviewsite directory.
To start the server run the following command.

Windows
>>>py manage.py runserver

Linux
>>>python manage.py runserver

The server will be running at LocalHost8000

http://localhost:8000/polls/  
This will show you the polls homepage where you can pick and vote on polls.

To create new polls or change existing ones, admin privileges are needed.
In the console run the following command.

Windows
>>>py manage.py createsuperuser

Linux
>>>python manage.py createsuperuser

After creating your username and password start the server again and go to
http://localhost:8000/admin/

This page will allow you to add new users, update questions, and add new questions.
Going back to /polls/ will allow you to see the updated questions.
