# Week_5
# Hello World Django App 
 
This is a basic Django web application that returns a "Hello World!" message in JSON format. 
 
## Getting Started 
 
Follow these instructions to set up and run the project on your local machine. 
 
### Prerequisites 
 
- Python (3.x recommended) 
- Django 
 
### Installation 

Navigate to the project directory: 

code 

cd project Name 

Install virtual environment

code
pip install virtualenv

Create a virtual environment (optional but recommended): 

code 

virtualrnv venv 
 

Activate the virtual environment (skip this step if you didn't create a virtual environment): 

On Windows: 

code 

Venv\Scripts\activat 

 
Running the App 

Start the Django development server: 

 code 

python manage.py runserver 
 

Access the "Hello World" JSON response in your web browser: 

http://127.0.0.1:8000/hello/ 

You should see the following JSON message: 

jsonCopy code 

{"Message": "Hello World!"} 

 
