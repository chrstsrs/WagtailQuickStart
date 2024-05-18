# Wagtail Quick Start

This is the quick start for a blog using Wagtail, as described in the official step-by-step guide.
To run the project, first download it, open a bash shell terminal and go to the projects folder.

### Create a virtual environment
```bash
python -m venv env
```

### Activate the virtual environment
```bash
source env/Scripts/activate
```

### Install project dependencies
```bash
pip install -r requirements.txt
```

### Create the database
```bash
python manage.py migrate
```

### Create an admin user
This prompts you to create the admin user account with full permissions. For security reasons, the password text won’t be visible while typing.
```bash
python manage.py createsuperuser
```

### Start the server
```bash
python manage.py runserver
```

### Access the Admin interface
In your favorite browser, go to
```bash
http://127.0.0.1:8000/admin
```
and you will see the login page. Use the credentials you entered as a superuser to access it. This is where you can create the webpages you like, uploading images and creating content.

### Stop the server
In the bash terminal type
```bash
  ^C
```

## Author

- Charisios Tsiairis[@chrstsrs](https://www.github.com/chrstsrs)
