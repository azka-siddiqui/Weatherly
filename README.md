# Weatherly

## Overview
A simple a easy-to-use website that allows people to quickly see both current and hourly weather conditions.

## Logic Flow
1. User enters a city or zip code into Weathery.
2. Validation (if city is valid, proceed, else show error message)
3. Fetch calls Open Weather's Current Weather Data API and gets (current temp, feels like temp, current conditions, sunset, sunrise)
4. Fetch calls Open Weather's One Call API for hourly data in 3-hour intervals for 5 days.
5. Data is formatted and rendered to DOM. 

## Used
1. HTML
2. CSS
3. JavaScript
4. Bootstrap 4
5. Open Weather API
