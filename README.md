# Spotify Data App

A Flask web app that allows sptotify users to view detailed information and statistics about their usage data. Also features an audio analysis and personality classification based on the user's top songs, deployed with Microsoft Azure.

Utilizes the Spotify Web API for authentication and data collection, and uses sklearn's Decision Tree Classifier for the personality classficiation.

<h2>Links<h2>
  
 - https://developer.spotify.com/documentation/web-api/
  
 - https://scikit-learn.org/stable/modules/tree.html


## Run Commands
   ## How to run locally
   
   - You must make a few changes to the code before attempting to run it locally, the following changes are in app.py
    
    
    '''
    # Redirect uri and authorization scopes
    redirect_uri = "https://myspotifydata.azurewebsites.net/home"
    scope = "user-top-read user-read-recently-played playlist-read-collaborative playlist-read-private"

    # UNCOMMENT TO USE FOR LOCAL TESTING
    # redirect_uri = "http://127.0.0.1:8000/home"
    '''
    
   - uncomment the local redirect url and comment out the azurewebsites redirect urls
