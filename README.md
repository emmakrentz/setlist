# Setlist prediction model
Using the setlist.fm and Spotify APIs to build out a propensity model to predict whether a given song from an artist will be played at an upcoming concert. There are a significant number of factors that may affect whether a song is played, including:

1. Relative popularity of the song
2. Relative popularity of the artist
3. Time delta between release of the song and date of the show
4. Size of the venue
5. Festival, album release tour, or other
6. Historical likelihood of the song being played
7. Time since previous show
8. Features of the song itself: danceability, energy, length
9. Number of times a song was released
10. Average setlist length

Using data collected in both these APIs, as well as from other open-source databases, we compile a tool to predict the setlist of an upcoming show. Eventually, this will be compiled into a Spotify App that then creates a playlist based on the model output.
