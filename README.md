# Wordle Solver

Still a work in progress, but mostly functional
This solves 99.6% of words in an average of 3.053 moves.

This approach is rather brute force, but essentially does the following:

1) Get a list of all eligible remaining solutions
2) Generate a frequency map for each column
3) Get a list of potential guesses and score them against the frequency map
4) Pick one of the guesses, grade it, and repeat



Words not solved within 6 moves
- joker
- boxer
- roger
- shale
- shave
- fight
- tight
- wound
- hound

TODO:
- ~~If a letter is "graded" "yellow", update $pattern to exclude char from that position~~
- when calculating word score, reward cross-discovery in solved positions