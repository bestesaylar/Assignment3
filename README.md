Hello!
This week, I’ve created a dynamic front end web application.
The purpose of this  project is to;
- Connect with API: weather, timezone and location.
- Include an interactive button element which response to click by changing the weather in F to celsius.
- Create a responsive screen size.

I pulled weather data from https://darksky.net/ and svg icons which changes depending on weather from https://darkskyapp.github.io/skycons/

This projects includes 4 files, namely index.html, a style sheet and app.js file and skycaps which includes the data that I’m using to get the icon images. 

The dark sky.net was free and I didn’t need to pay for an API key. I used fetch() function to pull/get the data from the server. After it fetched, I’ve converted the data to json and I used the data to get weather, timezone etc. 
While working I was using local host, and the api wasn’t letting me to acces data from local host so to get around that issue, I’ve found a website called cars-anywhere.herokuapp.com .Basicly, this acts as a proxy and It allow me to make request even from local host. So, I could have get the data this way. 

