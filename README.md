AirDelayPrediction
==================

Airplane delay prediction application based on HANA


This is your new Play 2.0 application
------------------------

This file will be packaged with your application, when using `play dist`.

To Predict a flight service:
http://flight-prediction.herokuapp.com/predictions/Airline/FlightNumber/Date/ArrivalAirportCode/DepartureAirportCode
e.g.  
http://flight-prediction.herokuapp.com/predictions/DELTA/DL123/2012-12-10/SFO/SEA

To Fetch Weather forecast
http://flight-prediction.herokuapp.com/weathers/CityName(.json/csv)
e.g.
http://flight-prediction.herokuapp.com/weathers/mountain%20view.csv
http://flight-prediction.herokuapp.com/weathers/mountain%20view.json

To Fetch Weather for specific date: 
http://flight-prediction.herokuapp.com/weathers/CityName/Date(.json/csv)
e.g. 
http://flight-prediction.herokuapp.com/weathers/mountain%20view/2012-12-11.json
http://flight-prediction.herokuapp.com/weathers/mountain%20view/2012-12-11.csv
