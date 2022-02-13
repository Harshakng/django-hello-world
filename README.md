This is a Django "Hello World" that includes a view of a JSON message in an HttpResponse object, rendered in bold by a template.

For displaying it in a web browser via local host, install Django, then on the command line / terminal, navigate to the project directory (/helloWorld) and enter:

python manage.py runserver

In a web browser navigate to the address:

http://localhost:8000/helloWorldApp/

To complete this file, we have made this steps as follows: A. Created a Django project

B. Created a web app within the project, including:

1. Modded the app's views.py file to hold a json message (stored in a local variable)

2. Created an app 'urlConf' (maps url patterns to views) in a urls.py file

3. Pointed the root 'urlConf' to the app 'urlConf'

4. Modded project settings.py file to include the app 

5. Migrated default database tables as necessary to build app

6. Created a template index.html file in the appropriate directory

7. Set a variable in index.html using Django template language and marked bold using html 

8. Loaded the template from the app's views.py file

9. Rendered view with template and returned as an HttpResponse object
