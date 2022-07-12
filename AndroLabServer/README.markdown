AndroLab Back-end Server Readme
==========

This project is the python2 backend server for the Android InsecureBankv2 application which can be found at https://github.com/dineshshetty/Android-InsecureBankv2


Python required libraries
-----

Install the below libraries using: easy_install <libraryname>

* flask
* flask-sqlalchemy
* simplejson
* cherrypy
* web.py

Alternatively just use:
pip install -r requirements.txt

Running the python server
-----
Create image from Dockerfile
docker build -t <IMAGE-NAME> .

Run your container
docker run -it -d -p8888:8888 --name <CONTAINER-NAME> <IMAGE-NAME>
