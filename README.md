# spotify-saved-tracks-dl

A command line utility which lets users download spotify tracks from albums, playlists, and his/her saved content as audio tracks from youtube

# 1.0 
Initial draft script available.

## Prerequisites
Run the below commands
* brew install youtube-dl
* brew install ffmpeg 

## Usage
* python savify.py 
* ~~./savify \<OAuthKey\> ~~

Replace ENTER\_YOUR\_SPOTIFY\_API\_KEY\_HERE and ENTER\_YOUR\_YOUTUBE\_API\_KEY\_HERE aptly

Get your  spotify OAuthKey from https://developer.spotify.com/web-api/console/get-current-user-saved-tracks/ (You will have to login to spotify to generate OAuth)
* Hit "GET OAUTH TOKEN" button
* Check "user-library-read" option (Check All Recommended)
* Hit "REQUEST TOKEN" button

Get your youtube API key by following this tutorial https://www.youtube.com/watch?v=JbWnRhHfTDA (You will have to login to your google account
