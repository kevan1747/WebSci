Kevan DuPont
duponk2

When the page is opened, the current location is obtained by HTML5 geolocation. I then pass the latitude and
longitude to the openweathermap API with the API key. This gives me the weather data for the location in a
JSON file. The icon and description are nested in an array in the JSON file, so I use a $.each() function to obtain 
those two pieces of data. I take the icon number and add it onto the end of the openweathermap image URL to
get the correct weather image. The description is just text so I append it to the associated element. I append the
rest of the data and add any units or do any necessary calculations. For the look of the app, I used bootstrap. I
created a small, compact app by using bootstrap's Panel setting. I placed the name of the location in the top
header, and organized the data within the box.

Resources:
http://api.jquery.com/jquery.get/
http://www.w3schools.com/html/html5_geolocation.asp
http://openweathermap.org/appid#use
http://openweathermap.org/weather-conditions
http://openweathermap.org/current#other
http://openweathermap.org/API
http://stackoverflow.com/questions/6027937/javascript-float-subtract
http://symbolcodes.tlt.psu.edu/web/codehtml.html#math
http://getbootstrap.com/examples/theme/
http://getbootstrap.com/getting-started/#tools
http://www.w3schools.com/js/js_operators.asp