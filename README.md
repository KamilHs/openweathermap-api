# Weather Forecast openweathermap

This project shows weather forecast for the requested city.

# Configuration

In the ```apiConfig.php``` file the ```api-key```from openweathermap must be assigned to a proper variable. Only ```units``` configuration may be changed.
```
const API_KEY = "<your_api_key>"; // Enter api key
const BASE_URL = "http://api.openweathermap.org/data/2.5/weather";
const MODE = "xml";
const UNITS  = "metric"; // Optional
```

# Usage

After starting the server open the ```index.php``` file and search desired city in input.

# Live Demo 
http://kamilhs.alwaysdata.net/openweathermapapi/