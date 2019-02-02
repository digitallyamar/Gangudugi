# Gangudugi
Django based CMS for blogs

# Getting started

After cloning this repo, follow these steps to get the CMS up and running on your local system:

### Step 1
Apply Django migrations to create relevant database with appropriate tables created within it. This can be achieved using the command:
```
cd Gangudugi
python manage.py migrate

```
### Step 2
With relevant DB now created, it is time to create Admin login on your Gangudugi Django based CMS. You can do so by running the following commands:
```

python manage.py createsuperuser
Username: Admin
Email address: <emailID>
Password: ***********
Password (again): ***********
Superuser created successfully.

```

### Step 3
With Admin login successfully created, its now time to test the CMS using the following commands:
```
python manage.py runserver
System check identified no issues (0 silenced).
February 02, 2019 - 21:22:38
Django version 2.1.5, using settings 'Gangudugi.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```
You can now go the following link http://127.0.0.1:8000/admin to access the admin login screen. Sign up with the previously created Admin credentials and you should successfully be logged into the Django Admin panel.

Play around by creating multiple new Posts and you should be good to go!
