# Summary
    Uses Openweathermap and sends an API request for current weather data. Compares the weather ID code to tell you the current days atmospheric 
    conditions via a sms text message

## Libraries/Modules
    import requests
    from datetime import datetime
    from twilio.rest import Client
    import time


### Usage
    In order to use this app for your own purposes, you will need to change a few items.
      -variable parameters, set to your current lat/long
      -Account SID
      -Auth Token
      

 #### Design implementations
    - In order to work more with APIs I have decided to use this version to text via the Twilio app



