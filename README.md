# Authentication-Django-and-Postgresql



![1_bWE-II6fsnV7my9vWLoyxQ](https://github.com/dharshu2323/Authentication-Django-and-Postgresql/assets/104815447/f92f86b6-c26d-4459-b3d8-249e7a6825c5)

Welcome to the Authentication-Django-and-Postgresql repository! This project implements user authentication using Django and PostgreSQL, providing a secure and seamless authentication system for web applications.

Django: A Python web framework.
PostgreSQL: A powerful, open-source relational database management system.
Create a database in postgresql and connect to django.



https://github.com/dharshu2323/Authentication-Django-and-Postgresql/assets/104815447/c2c9b66c-7bbd-4548-b3a2-869091457bba

To connect the django with database you can use the following commands👇in the settings.py

```DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME':'test1',
        'USER':'dharsh',
        'PASSWORD':'dharsh',
        'HOST':'localhost',
        'PORT':'5432'
    }
}
```
Form Handling: Utilizes advanced Django features for handling forms, views, and templates.

🔐 User Authentication:
Registration and Login: Users can register for accounts and securely log in.
Password Management: Secure password handling and storage.
Session Handling: Utilizes Django's built-in features for managing user sessions.
Permissions: Granular control over user permissions.

![Screenshot (136)](https://github.com/dharshu2323/Authentication-Django-and-Postgresql/assets/104815447/4bd3b3bb-3848-4006-a061-144b144291bf)



