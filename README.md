# ELEC50015 Smart Grid Information Server

This Flask app returns JSON data from 5 endpoints:

- `/sun` The current sunshine intensity
- `/prine` The current energy sell and buy prices
- `/demand` The current instantaneous energy demand for your household
- `/deferables` The list of today's deferable demands, which can be satisifed at any time during a specified window
- `/yesterday` The evolution of price and instantaneous demand from yesterday

The app is hosted at [https://icelec50015.azurewebsites.net/](https://icelec50015.azurewebsites.net/)

You can also run it locally: `flask run`
