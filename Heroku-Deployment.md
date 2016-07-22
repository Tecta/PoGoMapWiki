### Documentation

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?button-url=https://github.com/AHAAAAAAA/PokemonGo-Map/tree/develop&template=https://github.com/AHAAAAAAA/PokemonGo-Map/tree/develop)

This project supports deploying a new app to Heroku using the "Deploy to Heroku" button.  Clicking this button will walk you through setting up the project on your Heroku account, allowing you to set the various configuration values required to make the project run.

## Manually deploying to Heroku

To manually deploy this app to Heroku, perform the following steps:

    # Get a local copy of the project
    git clone https://github.com/AHAAAAAAA/PokemonGo-Map.git

    # Create a Heroku app for the project
    heroku apps:create

    # Set the required configuration parameters for the app, replace with your
    # actual values.
    heroku config:set AUTH_SERVICE=insertyourauthservicehere
    heroku config:set USERNAME=insertyourusernamehere
    heroku config:set PASSWORD=insertyourpasswordhere
    heroku config:set LOCATION=insertyourlocationhere
    heroku config:set STEP_COUNT=insertyourstepcounthere
    heroku config:set GMAPS_KEY=inseryourgmapskeyhere

    # Push the project develop branch to the master branch on Heroku
    git push heroku develop:master