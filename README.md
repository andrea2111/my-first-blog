# Blog

This project uses Python 3.7

## Getting started
You can clone the repository by running `git clone` and the project link.  

First create a virtual environment by running `C:\Users\Name\directory> python -m venv myvenv` where `myvenv` is the name of your `virtualenv`.  

Then start it with `C:\Users\Name\directory> myvenv\Scripts\activate`.  

Install the required libraries by running `pip install -r requirements.txt`.  

Initialize you database by running `python manage.py makemigrations blog` and then `python manage.py migrate blog`.  

Now you can start the application by running `python manage.py runserver`.
