
# About The Project


Flask_Blog is a simple blog based on Bootstrap blog theme and running on a python web framework: Flask. It is perfect for personal or company blogs. It includes a blog index, an about page, post page, contact page and more.

This blog support user authentification, login and registering.
And also article creation, modification and deletion from sqlite database.

The Main features are : 

- Jinja for web templating
- Navigation with RESTful routing 
- Post creation and deletion with WTForms
- Post comments with WTForms
- Database with SQLite and SQLAlchemy 
- Email contact with smtplib 
- Authenticating: Login and Registering with Flask-Login
- Front end with bootstrap 

# Start Up


Create a python3 virtualenv and activate it:

```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv -ppython3 ~/venv ; source ~/venv/bin/activate
```

Clone the project and install it:

```bash
git clone git@github.com:OlivierLpp/Flask_Blog.git
cd Flask_Blog
pip install -r requirements.txt              
```
Run it localy:
```bash
gunicorn main:app
```


