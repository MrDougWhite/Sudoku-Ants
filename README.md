# Sudoku-Ants
Exploration of Object Oriented Sudoku Puzzle solving by logical steps a human should be able to follow, where the steps are discovered by instantiated solver objects.
The project is a vehicle for familiarization with GitHub development, as well as with OO programming.

The idea is that the experienced Sudoku player develops a set of strategies by which the only possible number that could 
belong in a square is deduced from the information initially given, and what has since been deduced.
This continues, square by square, until the game board is completely filled in.  It would be interesting to have a 
computer program attempt to use these human like strategies to 'solve' a Sudoku puzzle.

Computers are not human.  A standard nine-by-nine Sudoku grid is not so large that a brute force iterative or recursive 
solution test, a trial and error process, would take too long to reach a solution.  But a human would be bored to death by 
some running explanation such as 
  Describing when all possible arrangements of the board with a 2, 4, 5 or 7 in the second square were tried,
  resulting in inconsistencies, leaving the only possible number that could be in the square is '8'.
  
A human would want to see a solution as he or she would solve the puzzle.  The envisioned end state is narration of a step-wise strategy that a person might apply to solve a puzzle in pen.  A pen is mentioned because that is how Doug White solves
his puzzles.  Erasures seem bad form.

During development, two possible extensions are anticipated.  First, the hardest Sudoku puzzles cannot be solved without
conjecture, picking one of two possible values for a square and running out the consequence, looking to see if a 
contradiction is created.  This means that the game itself needs to transition into a hypothetical instance, within which 
all the strategies are played out.  

As a second extension, the dimensionality of the board may change.  Super Sudoku exist of nine 4x3 and nine 4x4 blocks.
It would be nice to have this project extend to those variants of the game board.

Also, the characters for the grid do not need to be the nine digits, but could be letters or even arbitrary symbols.

The ants come into play as the Object Oriented approach is used.  The strategies are prompted by blank squares, by iteration
among the numbers, by focusing on a block at a time.  The nine blocks,the 81 squares and the 9 instances of all nine of the
digits all seem to pop into mind for consideration.  (Even more strategies are used).

What it is thought the solution might do is spawn these many instances of unfulfilled 'wants', all vieing for the opportunity
to deduce something.  As they satisfy those wants, they fall dormant.  Order is maintained by doling out time to see
if a contribution can be made.  The human solver does this, trying separate strategies, usually considering
the easier ones first.



could be followed in pen.


