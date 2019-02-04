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

Play around by creating multiple new Posts from the Admin panel's **"Posts"** link and you should be good to go!

### Step 4
Now that we have created a few posts through the Django Admin panel, we can again checkout these list of posts displayed on the home page by going back to http://127.0.0.1:8000/

We can also see a '+' symbol on the top right corner of the page if you are already logged in as Admin. This is a button that can be used by a logged by an Admin user to create new posts.

Go ahead and click on the '+' symbol and create a new blog post. Once you hit the save button, the blog post should be published and become visible in its unique Django blog post url. In the same page, you should also be able to edit the post through the edit button, represented with a 'Pen' icon.

After playing around these options, once you come back to the Django application's home page at http://127.0.0.1:8000/, you should now also see this new post visible at the top of the Django App home page along with other blog posts.

If you log out of the Admin panel, you should **not** be able to see the '+' symbol to add a new Django blog post or edit an existing Django blog post anymore.