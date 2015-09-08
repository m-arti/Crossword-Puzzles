# Crossword Puzzles
Solving crossword puzzles through an exhaustive search.

# Examples
#####15 x 15 grid
![Example 1](https://www.dropbox.com/s/dl9er5ccssqcwzg/puzzle.JPEG?dl=1 "Example 1")

##### 5 x 5 grid (fluke)
![Example 2](https://www.dropbox.com/s/myy657seavmrvg5/Puzzle2.JPEG?dl=1 "Example 2")

##### 7 x 12 grid
![Example 3](https://www.dropbox.com/s/evh8pwrfx1z87z5/Puzzle3.JPEG?dl=1 "Example 3")


# To-do

### Minor
- Make code neater / rename functions.

- Timing analysis: plot a graph of number of row & columns against time taken to solve puzzle.

- Result analysis:

 * What effect does adding more vowels to the grid have on the results? (Using ```RandomChoice[CharacterRange["A", "Z"]]``` to generate grid yields mostly three-letter words.)

 * How can the grid be generated such that it yields more results longer than three letters?

- How to visualise palindromes and repeated words.

### Major
- Try 3-dimensional solving (3D graph) and visualise, distinctly, "streams," or lines connecting letters that form words. In 3D, the four-colour visualisation system will no longer work.

- Try solving actual cross-word puzzles.

- Try to device a learning mechanism which can be used to make solving future puzzles easier.
