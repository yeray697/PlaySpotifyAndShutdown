## Description
Shutdown your pc after X minutes and play a Spotify playlist during 10 minutes (default).

## How to use it
#### Setting a playlist
To change the spotify playlist, change the URI variable. In order to get your playlist URI, go to Spotify, right click over your playlist and click on "Copy Spotify URI"
#### Time options
##### Passing one integer:
The integer means how many minutes will pass before to start the playlist. After that, your computer will shutdown after 10 minutes

###### Example:

  pss 5       ->     Music starts to play after 5 minutes and your pc is shutdown after 10 minutes (default)

Passing two integers:
The first one means like the previous one. The second means how many minutes will be playing spotify before to shutdown

###### Example:

  pss 5 8     ->     Music starts to play after 5 minutes and your pc is shutdown after 8 minutes
  
#### *** Note: 'pss' is the name of the script!
