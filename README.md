# SpotifyRec

This Jupyter file includes code to:
Import the required toolboxes
Connect to a spotify dev account
Organize and pre-process data from provided playlists
Build and train and neural network regression model
Generate song reccommendations and filter them through model
Upload model-filtered song recommendations to a provided spotify playlist
To run this notebook you will need a spotify dev account. To create one, go to this link and setup an account: https://developer.spotify.com/dashboard/
Once you have a dev account, go to the dashboard tab and create an app. 
![image](https://github.com/user-attachments/assets/10dc76f5-139f-4651-b8d9-7b13d9b90822)

Navigate to your app and locate your Client ID and Client ID Secret.
![image](https://github.com/user-attachments/assets/39b2a1c5-f689-45d7-884a-8e21477685ec)

Copy these two client codes into the notebook code cell below labeled "Authorization". 
Next go to your spotify dev project and click "Edit Settings" and under the "Redirect URL" section, place your desired redirect url (ie: https://www.google.com/) for authorization and select save. 
Place your redirect url into notebook code cell below "Authorization".

