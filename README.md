# Set up environment
## Create a virtual environment
```
conda create -n db_app python=3.8
```
## Install required packages
```
pip install -r requirements.txt
```
# Initialize the app
```
python manage.py makemigrations
python manage.py migrate
```
# Run the server
```
python manage.py runserver
```