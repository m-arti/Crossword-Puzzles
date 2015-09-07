# Crossword Puzzles
Solving crossword puzzles through an exhaustive search.

![Example Image](https://www.dropbox.com/s/2xovi797weiry6z/puzzle.JPEG?dl=1 "Example")

#To-do

### Minor
- Make code neater / rename functions.

- Timing analysis: plot a graph of number of row & columns against time taken to solve puzzle.

- Result analysis:

 * Using ```RandomChoice[CharacterRange["A", "Z"]]``` to generate grid (often) yields more words in the horizontal direction, followed by the vertical direction, and fewer words in the main diagonal & antidiagonal directions.

 * What effect does adding more vowels to the grid have on the results?

- Analyse the problem of 'squeezed' view when grid order is high (≥ 10 rows & columns).

- How to visualise palindromes and repeated words.

### Major
- Try 3-dimensional solving (3D graph) and visualise, distinctly, "streams," or lines connecting letters that form words. In 3D, the four-colour visualisation system will no longer work.

- Try solving actual cross-word puzzles.

- Try to device a learning mechanism which can be used to make solving future puzzles easier.
