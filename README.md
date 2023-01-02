# Python practicum 2022, 1st task
Flask app:
* route /welcome, responds with the string "welcome" 
* route /welcome/home, responds with the string "welcome home" 
* route /welcome/back, responds with the string "welcome back"

# Python practicum 2022, 2nd task
Evolve the previously created flask app:

Weather report

✅ Get a weather report for a city of your liking via API call
* API doc: https://openweathermap.org/current#name
* API Key: shared via another channel

✅ Create a route /weather which responds with received data
* display city name and current temperature in Celsius
* consider using a template to render and display data

✅ Optional task – let the user pick a city

# Python practicum 2022, 3rd task
Continue evolving the previously created flask app:

✅ Get geographic coordinates for a city of your liking via an API call
* API doc: https://openweathermap.org/api/geocoding-api

✅ Get historical data from dev.meteostat.net via one of these methods:
* JSON API
* Python library
* Bulk data

✅ Display one year of temperature history - min., max., average
* Use the graphical form of representation – matplotlib module

✅ Create a route /weather_history to display data
* Show city name and chart with temperature data, including legend (names of axis, description of data)
* In addition, separately display values for min., max. temperature, the date it was recorded, and the average temperature for the whole range.
* Provide a download link for an Excel document with temperature data (raw data)
* Provide a download link for a PDF document with a temperature chart (graphical data)

✅ Additional advanced task: Send notification of the temperature
* Create a route /notification
* Possible communication channels:
* * a push notification via SIGNL4 or similar service: https://www.signl4.com/
* * e-mail notification
* * SMS message
* Trigger the notification by:
* * Pushing a button on your webpage
* * Setting up a notification when a trigger temperature is reached
