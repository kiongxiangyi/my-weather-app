 1. Inside the App component, create 2 states (lat & lng)
 2. Get the longitude and latitude of the user and update the state (https://developer.mozilla.org/en-US/docs/Web/API/Geolocation/getCurrentPosition)
 3. Create a new component Weather and import it into App
 4. In this component Fetch the API and log the result (Only when we have the lat/lng) https://api.open-meteo.com/v1/forecast?latitude=52.52&longitude=13.41&daily=weathercode,temperature_2m_max&timezone=Europe%2FBerlin / https://open-meteo.com/en/docs
 5. Display the 7 days of weather, just with text in a table
 6. Create an object (not with all the data) in which we have the WMO code and the correponding image (https://open-meteo.com/en/docs / https://fontawesome.com/icons/categories/weather) and use it in the table
