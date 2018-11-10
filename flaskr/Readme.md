## Running virtual env locally for a Flask app using python 3.7.*

# Flask Tutorial - Blog

A Blog - Flask app

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
python 3.7 https://www.python.org/downloads/
python dev environment https://cloud.google.com/python/setup
flask http://flask.pocoo.org/docs/1.0/installation/#installation
```

### Installing

A step by step series of examples that tell you how to get a development env running

1. Create a virtual environment

```
mkdir myproject
cd myproject
python3 -m venv venv
```
2. Activate the environment


```
. venv/bin/activate
```

3. Navigate to your project directory and install dependencies:

```
cd YOUR_PROJECT
pip install  -r requirements.txt
```

4. Run the application:

```
python main.py
```

5. In your web browser, enter the following address:

```
http://localhost:8080
```


## Running the tests

Explain how to run the automated tests for this system

1. Activate virtual environment at `flaskr` folder `. venv/bin/activate`
2. Convert the flaskr project as a installable by running `pip install -e .`
3. Keep the `tests` folder at same level as `flaskr` directory
4. Install `pytest` and `coverage` by running command `pip install pytest coverage`
5. At `flaskApps` folder run the tests as `python -m pytest` Refer: https://github.com/pallets/flask/issues/2908 



## Deployment

Follow the instructions below to deploy app onto google app engine

1. Deploy the app by running the following command from the PROJECT directory:

```
gcloud app deploy
```

2. Launch your browser and view the app at http://YOUR_PROJECT_ID.appspot.com, by running the following command:

```
gcloud app browse
```

## Built With

* [Flask](http://flask.pocoo.org/docs/1.0/) - Flask web framework
