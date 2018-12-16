LIRI-NODE-APP

TITLE: Liri-Node-APP

DESCRIPTION:
In this assignment,  we created a LIRI app using Node.js. LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a _Language_ Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

MOTIVATION: 
To use node.js and using Spotify API.

TECHNOLOGY USED: 
Node-SPotify-API, Axios, Moment, DotEnv

WHAT EACH COMMAND DOES:

1. node liri.js concert-this <artist/band name here>.
This will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal.

![concert-thisimage](https://user-images.githubusercontent.com/43328718/50049155-4f342f00-00a3-11e9-8075-4f731a04f184.PNG)

2. node liri.js spotify-this-song <song name here>. 
This will show the following information about the song in your terminal/bash window

     * Artist(s)

     * The song's name

     * A preview link of the song from Spotify

     * The album that the song is from

![spotify-this-songimage](https://user-images.githubusercontent.com/43328718/50049152-3fb4e600-00a3-11e9-83c0-3e2a3890f0e5.PNG)


3. node liri.js movie-this '<movie name here>.
This will output the following information to your terminal/bash window:

       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.
       
 ![movie-this](https://user-images.githubusercontent.com/43328718/50049154-4b081180-00a3-11e9-8744-752a35718273.PNG)
 
 4. node liri.js do-what-it-says. 
 It should run `spotify-this-song` for "I Want it That Way," as follows the text in `random.txt`.
  

![do-what-it-say](https://user-images.githubusercontent.com/43328718/50049156-53f8e300-00a3-11e9-8ed7-32b2f15481be.PNG)


In addition to logging the data to the terminal/bash window, the log.txt output the data to a .txt file.

This is included in my portfolio. 








