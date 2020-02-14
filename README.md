# finalfapro
Full FA Engineering week project

This project is focused on building a data API in Python. This service will allow you to create and retrieve posts for a journal.

Docs
Get an entry
Get the details of a specific journal entry, given the entryid

URL : /diaryentry/<entryid>

Method : GET

Get all entries
Get the details of all journal entries

URL : /diaryentry

Method : GET

Create a new entry
Create a new diary entry in our journal

URL : /diaryentry

Method : POST

Provide details of entry to be created.

{
    "title": "string",
    "description": "string"
}
Deployment
We will deploy our API using pythonanywhere.com, which will allow us to easily expose our API to the public.

Steps:

Sign up for an account with your email at https://www.pythonanywhere.com/registration/register/beginner/
Click on "End Tour"
Once you're in the main screen, click on the Web tab
Click on Create new web app
Click on Next
Select Flask
IMPORTANT: Select Python 3.8
Rename the file to app.py
You should now have a basic Flask API setup!
Upload/overwrite the app.py file with our Sublime text files from our computers
Upload the database.JSON file to your file list
Hit Save + Click the little refresh button
Test the API!!!
Create a Bash Console from the Pythonanywhere page (Way to interact with a computer through typing)
Create a virtual environment using: mkvirtualenv venv --python=/usr/bin/python3.8
Once you're in your virtual environment, run pip install flask-cors
Update your virtualenv in the Web tab as /home/{username}/.virtualenvs/venv
Uncomment the lines related to CORS in app.py
Save, Refresh and then reload web app
Test the API! You're done!
