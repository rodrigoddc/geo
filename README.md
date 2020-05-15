# geo
Django web app with geolocalization based on Geek University course

## Main Requirements
Python3.x.x
Django2.x.x


## How to use
Create a folder to store this project. Open this folder on terminal and run the following commands

### 1. Clone the project
git clone https://github.com/rodrigoddc/geo.git

### 2. Create a virtual environment
python3 -m venv venv

### 3. Activate the the virtual environment previously created
on linux: source ./venv/bin/activate
on windows: ./venv/Scripts/activate.bat

### 4. Installing libs
pip install -r requirements.txt

### 5. Creating database
python manage.py migrate

### 6. Running
python manage.py runserver

After that, you'll be able to access the project at 127.0.0.1:8000 or localhost:8000 on your browser
