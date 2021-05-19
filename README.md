# Fridge Data Backend

A simple hard coded backed that delivers data on fridge cooldown and warm up times.

## Technologies

* Python
* Flask
* virtual environments
* Flask-cors

## Running The Application

The application user python 3 and virtual environments.

* Create and activate the virtual environment:

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

* Run the application on port 5000:

```
FLASK_ENV=development flask run
```

The endpoint should be accessible at [http://localhost:5000/fridge-stats](http://localhost:5000/fridge-stats)