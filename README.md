

For this assignment, you will make a simple "game" that does the following:
* accepts a search term on the command line (e.g., a user should be able to run your game with '$ python mygame.py "Harry Potter"''
* performs a search on wikipedia using the search term
* takes the content of the top 5 pages returned by the search, and determines the most common adjectives across those pages
* draws a "ball" representing each of the top 6 adjectives
* allows the user to "pop" each balls by typing the first letter in the word contained in the ball

For a demo of how the game should work when it's complete, see the demo.

Yes, that's a pretty arbitrary game and it's not really all that fun to play. But it's a GREAT exercise to help us find out if 507 would be redundant for you. 

In order to complete this assignment, you will need to quickly figure out how to install and use three Python libraries that you most likely have never used (though if you have, it's pretty likely that 507 is overkill for you): wikipedia, nltk, and pygame. You will aslo need to be reasonably conversant with Python data structures and be able to map a high-level program description into a working (small) program design.

I have provided some starter code that demonstrates how to render stuff using pygame. You will have to add the following functionality:

* accepting command line arguments
* searching wikipedia
* using nltk to parse the contents of wikipedia pages
* drawing balls with the most common adjectives extracted from wikipedia pages
* allowing the user to delete balls using the keyboard
* when all balls are deleted, display game over screen