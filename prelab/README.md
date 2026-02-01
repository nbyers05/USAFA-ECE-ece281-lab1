# ECE 281 Lab 1 Prelab

## Prelab questions

### Truth Table

| Month | A | B | C | D | Y | 
|-------|---|---|---|---|---| 
| N/A   | 0 | 0 | 0 | 0 | X | 
| JAN   | 0 | 0 | 0 | 1 | 1 | 
| FEB   | 0 | 0 | 1 | 0 | 0 | 
| MAR   | 0 | 0 | 1 | 1 | 1 | 
| APR   | 0 | 1 | 0 | 0 | 0 | 
| MAY   | 0 | 1 | 0 | 1 | 1 | 
| JUN   | 0 | 1 | 1 | 0 | 0 | 
| JUL   | 0 | 1 | 1 | 1 | 1 | 
| AUG   | 1 | 0 | 0 | 0 | 1 | 
| SEP   | 1 | 0 | 0 | 1 | 0 | 
| OCT   | 1 | 0 | 1 | 0 | 1 | 
| NOV   | 1 | 0 | 1 | 1 | 0 | 
| DEC   | 1 | 1 | 0 | 0 | 1 | 
| N/A   | 1 | 1 | 0 | 1 | X | 
| N/A   | 1 | 1 | 1 | 0 | X | 
| N/A   | 1 | 1 | 1 | 1 | X |

### Boolean Equation

$$
Y = AD' + A'D
$$

### Digital Simulations

In this folder are also Digital templates for you to complete and simulate.  Do not change the file names or the input and output labels in Digital otherwise the autograder will not work.  The autograder will look in the prelab folder for the files.

Complete all three circuits using the various approaches (generic multiplexer symbol, 74151 multiplexer chip, and a sum of products using and/or logic gates).

You may also wish to run test cases.  The first two rows of the truth table have been added to the Digital simulation files as a test.  You may wish to edit the test to add more rows and fully cover all possible cases but this is not required.

## Submission

1. Make sure all prelab files are in this folder
2. Commit all files
3. Push to GitHub
4. Submit to Gradescope
5. Verify submission
