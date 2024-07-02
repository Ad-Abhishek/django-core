# create VE:

`py -m venv .venv`

# activate VE

`.venv/Scripts/activate `

# install Django

`pip install Django`

# update pip

`py -m pip install -U pip`

# to open py repl:

`py<enter>`

`import Django`

`print(Django.get_version()) ` # get django version

`quit()`
``

# start a new Django project:

`django-admin startproject myproject`

# enter the top level myproject(project_name):

`cd .\myproject\`

# run server with customized PORT

`py .\manage.py runserver 8001`
--> default PORT is 8000
