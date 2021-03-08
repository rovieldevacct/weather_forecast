# weather_forecast
This is a laravel project done with a latest version which is 8 for testing purpose only.
The design might me lacking a lot since front end is not my strong point but I made it simple and clean.
first download the file from this repo and extract it.
you can access it by using http://localhost/weather_forecast/
In this menu, you need to click the button to redirect you to the weather forecast menu.
In the forecast menu, you may need to select a city that you want to see the forecast for the next 5 days every 3 hours.
I only used a selective city names to lessen the load times of the sample city but in the config it is ready made to switch to show all the list of city but might take a lot of time to load.
Selecting the city in the dropdown menu to auto load the weather details of the forecast.
There will be 2 column on the result.
1st column: the current day forecast for the selected city
2nd column: the list of weather forecast for the next 5 days for every 3 hours interval.
You may click on each day of the forecast to view the much detailed version of the weather forecast per day.
I added a screenshot on how it looks on mobile but the UI is kinda all messed up.
UI is somewhat dynamic when browser resolution is changed.
API key is stored in the .env file.
