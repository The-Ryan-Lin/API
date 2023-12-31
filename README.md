# API

This folder contains previous work on using APIs, including accessing, authorising, creating environment variables (.env files), importing .env files and API keys, and connecting to and retrieving data.

1. __Investigating Bitcoins Price Index:__ Making_a_GET_request_to_an_API_Bitcoin.ipynb

Using the two public APIs below, I explore Bitcoin and its potential use and growth in the United States.
* The current Bitcoin Price Index (https://api.coindesk.com/v1/bpi/currentprice.json (Links to an external site.))
* USA population data (https://datausa.io/api/data?drilldowns=Nation&measures=Population (Links to an external site.))

2. __Using the OpenWeather API:__ Using_the_OpenWeather_API.ipynb

I use the OpenWeather API to obtain current and historical weather data on the chosen location generating the coordinates. I set up an OpenWeather account, created an Environment variable for the API key, imported the key into Jupyter Notebook, and generated a simple request to ensure I can correctly make an API call. I then obtained the coordinates of chosen locations, retrieved the weather data for these locations between 1983 and 2023, and compared the results.
