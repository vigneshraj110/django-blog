Django-Blog Website

This is a basic blog application built with Django, allowing users to perform CRUD (Create, Read, Update, Delete) operations on blog posts. 
The application also includes a simple API for interacting with the blog posts programmatically.

Features:
  Create: Add new blog posts with a title and content.
  Read: View all blog posts or a specific post.
  Update: Edit existing blog posts.
  Delete: Remove blog posts.
  Simple API: Interact with blog posts via a RESTful API.
  
Requirements:
  Django 2.2.7 : pip install Django==2.2.7
  django-crispy-forms : pip install django-crispy-forms
  Pillow : pip install Pillow

Usage :
  Make Sure you are in directory same as manage.py
  python manage.py makemigrations
  python manage.py migrate
  python manage.py runserver
  
Atlast, In your web browser enter the address : http://localhost:8000
