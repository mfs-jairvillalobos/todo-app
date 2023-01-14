# API Todo App
***
## Description:
A simple app written in Python with the framework FastAPI. It shows how to create a basic API based in a structure of 3 layers:

## Run Locally
To run the commands you must be on the root of the repository


### Local execution
🚨 NOTE: You must be having installed python3.7 or higher in your local machine
### LINUX:
``python -m venv venv``

``./venv/bin/activate``

``pip install --no-cache-dir -r requirements.txt``

``uvicorn main:app --reload``
### WINDOWS:
``python -m venv venv``

``.\venv\Scripts\activate``

``pip install --no-cache-dir -r requirements.txt``

``uvicorn main:app --reload``

this will start the server to the default host: http://127.0.0.1:[port number]

you can see the swagger documentations in: http://127.0.0.1:[port number]/docs

***

## FastAPI documentation

### Main page
https://fastapi.tiangolo.com

### routers section
https://fastapi.tiangolo.com/tutorial/bigger-applications/#import-fastapi
