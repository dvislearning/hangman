# hangman

Hangman is an exercise in I/O read/write and serialization
from [TheOdinProject](http://www.theodinproject.com/ruby-programming/file-i-o-and-serialization).

It randomly selects a word from an external list between 5 and 13 letters long.  The player gets 8 guesses to figure out what the word is,
by typing out one letter at a time.  An ASCII string of a hangman is manipulated whenever a player guesses incorrectLy.

Players also have the option to save the current state of their game and reload it in the future.  This is done using YAML.

Lastly, players have the option to see which letters they have already chosen.