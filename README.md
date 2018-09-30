# Local-Spotify-Web-Connect-Api-Python
a simple python script that allows you to control playback of spotify connect without the need of a local server

## How To Use
Follow these instructions to create a spotify app<br>
https://developer.spotify.com/documentation/general/guides/app-settings/<br><br>

The name and description are up to you.<br>
Add the whitelisted redirect url 'http://Localhost'<br><br>

Then copy and paste an Client_id and Client_secret of the app into the constants.py file<br><br>

From there you can just run <br>
```python3 spotify.py```<br>
to authorize it. Copy and paste the url printed from the script into your browser and click ok to authorize. You will then be redirected to a url that looks like http://localhost?code=XXXXXXXXXX ect<br>
Copy and paste that url back into the terminal to complete authorization. <br><br>

Now you can just call the provided script methods to play, pause, set the volume, get devices and playlists.<br>
This authorization flow works for the rest of the api as well so feel free to browse around https://developer.spotify.com/documentation/web-api/reference/ to see what other api endpoints you can add to the script.
