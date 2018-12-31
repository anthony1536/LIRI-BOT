# LIRI-BOT

(VIDEO DEMO): https://drive.google.com/open?id=1zkn5JIEi7gefiBeIeM9OqIv04soyrSJo

What does this Project Do?

Homework for week 10.
The assignment required use of several node libraries as well as several different api.
The node application "liri.js" is prompt driven using the node inquirer package and takes in these commands:
    
    1. `concert-this`
        This will show information of the keywords the user inputed giving concert locations/information

    2. `spotify-this-song`
        This will show information of the song based on the keywords inputed by the user.

    3. `movie-this`
        This will show information of the movie based on the keywords inputed by the user.
    
    4. `do-what-it-says` - 
        This will output search results based on the content of "random.txt" file.
        

This assignment used various node.js methods, performing api calls, json parsing, data storage and using multiple NMP packages.

How to use the project -

    1. Begin: user will type "node liri.js" in Terminal
    Next: user will input one of:

    concert-this - user must input a performing artist to search concert offerings and confirm the selection.
    spotify-this-song - user must provide a song title to search for and confirm the selection.
    movie-this - user must provide the title of a movie to search for and confirm the selection.
    do-what-it-says - once selected, the remaining prompts are ignored (with the exception of the confirmation prompt).
