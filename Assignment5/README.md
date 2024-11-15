# Assignment 5 Instructions

## Go to http://djangoproject.com then download and install the Django Web framework (and SQLite if you are not using a Windows-based PC, because it comes for free with Python 2.5+ for Windows).

### a) Execute

- ‘django-admin.py startproject helloworld’ to start your project, and then

- ‘cd helloworld; python ./manage.py startapp hello’ to start your app. (2 marks).

### b) Edit helloworld/hello/views.py to include this code (2 marks).:

- from django.http import HttpResponse

- def index(request):

- return HttpResponse('Hello world!')

### c) In helloworld/settings.py, add 'hello', to the INSTALLED_APPS variable (in any position of the tuple) (2 marks)..

### d) In helloworld/urls.py, replace the commented-out line (2 marks).:

- "# (r'helloworld/', include('helloworld.foo.urls')),"

- with this (uncommented) line:

- "# (r'^$', 'hello.views.index'),"

### e) Execute ‘python ./manage.py runserver’ and visit http://localhost:8000 to confirm that your code works and “Hello world!” does show up on your browser. Change the output to something other than “Hello world!” (2 marks)..

## Provide screenshots for each task.

