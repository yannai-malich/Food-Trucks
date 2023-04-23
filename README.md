SF Food Trucks
===

> San Francisco's finger-licking street food now at your fingertips.

![img](shot.png)

This is a fun application to accompany the docker curriculum. The app is built with Flask on the backend and Elasticsearch is the search engine powering the searches. The front-end is built with React and the beautiful maps are courtesy of Mapbox.


## Application Architecture
The application is comprised of two services:

(1) A Python Server which serves both data and a JS based UI

(2) An ElasticSearch Server which hosts the data and allows searching

## Configuration
The ElasticSearch connection details are hard-coded into app.py
The Flask Server runs on port 5000

## Building & Running the app
In order to build the app you will need:

(1) Python

(2) Pip

(3) NodeJS & NPM

## Steps:

(1) npm install

(2) npm run build

(3) pip install -r requirements.txt

After building you can start the app by running `python ./app.py`

