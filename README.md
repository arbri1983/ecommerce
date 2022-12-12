## Running this project

To get this project up and running you should start by having Python installed on your computer. 
It's advised you create a virtual environment to store your projects dependencies separately. 
You can install virtualenv with

```
pip install virtualenv

```
virtualenv env
```

That will create a new folder `env` in your project directory.

```
source env/bin/active

```
Then install the project dependencies with

```
pip install -r requirements.txt

```
Now you can run the project with this command

```
python manage.py runserver

```

**Note** If you need payments to function, it will be need to enter your own Stripe API keys into the `.env` file in the settings files.
---
