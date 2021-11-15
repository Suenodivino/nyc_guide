# <center>**NYC Guide Tour**<center>

Project completed alone by Dario Pena

Github username: Suenodivino

# **Create and run a virtual environment using venv in VS Code**

1. Create a directory or folder in VS Code. Type: **`mkdir *folder name`***

2. Change directories into folder you created. Type: **`cd *folder name`***

3. To create a virtual environment for directory you created, type: **`python3 -m venv django-env`**

4. To run the virtual environment if you are using Windows Powershell, type: **`django-env\Scripts\activate.bat`**

5. To run the virtual environment if you are using Windows Bash, type: **`source django-env/Scripts/activate`**

6. To run the virtual environment if you are using Unix or MacOS, type: **`source django-env/bin/activate`**

7. To deactivate the virtual environment, type: **`deactivate`**

# **Instruction on how to install project dependencies with pip**

1. To install Django, on the command line type: **`pip install django`**

2. Create a requirements.txt file to support django. Type: **`pip freeze > requirements.txt`**

3. Check to see if file is within the directory you created. Type: **`cat requirements.txt`**

# **How to run the django application**

1. Depending on the type of computer you are using, type: ***ex. Windows Bash:* `source venv/Scripts/activate`**

2. To start your project and create a project name, type: **`django-admin startproject *project name`***

3. To start the project you created, type: **'python manage.py startapp *`project name`***

4. To run the server, type: **`python manage.py runserver`**