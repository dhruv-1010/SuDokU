# Sudoku Solver using Recursion and Backtracking
**javascript sudoku solver** 
In this Project we are going to implement a simple sudoku solver backtracking Algortihm with vanilla Javascript,HTML and BootStrap 5 CSS Library with Node Js as backend server.
<br>
<i> Sudoku is a popular game from French origin it's a logic-based, combinatorial number-placement puzzle. In classic Sudoku, the objective is to fill a 9 × 9 grid with digits so that each column, each row, and each of the nine 3 × 3 subgrids that compose the grid contain all of the digits from 1 to 9.</i>

![image](https://user-images.githubusercontent.com/96680040/218298376-a0d8f219-9e2a-4936-bfb0-2f782f3c542d.png)
<h6>a common sudoku board</h6>
<h1> Key Idea </h1>
<h4>The Key idea is to use Recursion </h4>
The important steps are
<ul>
<li>To check out all possible cases by passing the value in empty space form 1 to 9</li>
<li>Check if the value is Valid by checking the 3 check function i.e
  <ul>
  <li>Number shouldn't exist in the whole row
  </li>
  <li>Number shouldn't exist in the whole column
  </li>
  <li>number shouldn't exist in the smaller box
  </li>
  </ul>
</li>
<li>if valid change the value in the board and pass the board into recursion and if the answer doesn't exist for any inside calls just backtracking it.</li>
<b>If the Solution doesn't exist we return false.</b>
</ul>
