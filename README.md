# Music_app_test

Music App
      
Music.dat : this file contains records about music songs. Each record Is scion of the following fields:

  song name; artists or group; genre 1; genre 2; ....; genre N

Where the song name and the artists or group are strings, inciuding spaces, and genres are strings composed of a single word. A song may belong to
Many genres, which number Is not known In advance.

Users.dat : this file contains records about the users of the app. Each record is composed of the following fields:

  name and surname; preferred genre 1; preferred genre 2
  
(Where each user has exactly two preferred genres.)
The Python program associates and prints to screen every user the list of songs according to the user's genre preference; moreover the songs
Suggested fo each user must be printed after the name and sumame (see the example below).
Songs with preferred genre 1 should be listed before songs in the preferred genre 2. A song cannot be displayed more than once for a single user. The
output for each preterred genre must be in alphabetic order.

Per every user, the output message format Is the following:
    Name and Surname number of songs is:
      -song
      -song
      -song
