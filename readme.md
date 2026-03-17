

- Clone this repo
- 'cd' to root folder
- delete data folder
- npm i to install dependencies
- setup .env with:
    - PORT
    - CITY
    - API_KEY from openweather
- npm i to install dependencies
- node fetchWeather.js to create/update folder
- node ap.js to start server

- Open browser on PORT to see weather and graph

## Using Docker

- cd into root folder
- Open your docker Desktop
- Make sure you are on same path as dockerfile
- Open your terminal run:
    - 'docker build -t <app-name>:<tags>' . or 'docker build -t weatherapp' . to Build an image on Dockerfile
    - 'docker run -p ,local-port>:<container-port><image-name> or docker run -p 3000:5000 weatherapp.js - to run a container based on an image.

## Tests

We have tests to check if files inside the data folder is correct