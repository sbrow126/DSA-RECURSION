# DSA-RECURSION

Counting Sheep
What is the input to the program? 3 (a number)
What is the output of the program?  The input number recursively subtracted counting down sheep until zero with text output for each call.
What is the input to each recursive call? The previous input number minus one
What is the output of each recursive call? A print of text counting down the sheep

Power Calculator
What is the input to the program? X and Y (2 integers greater than 0)
What is the output of the program? The exponent that results in X^Y
What is the input to each recursive call? X and (Y minus 1)
What is the output of each recursive call? X times the call to power calculator, with X and Y minus 1 as parameters
Reverse String
What is the input to the program? The string
What is the output of the program? The string in reverse
What is the input to each recursive call? The call to the function, with the first letter removed from the original string.
What is the output of each recursive call? Once the base case of 1 letter remaining is hit, that 1 letter is returned and added to an array.

Nth Triangular Number
What is the input to the program? N
What is the output of the program? The count of the nth triangle (number of dots)
What is the input to each recursive call? N minus 1
What is the output of each recursive call?  Returns n plus the call to the function, with n-1 as the parameter


String Splitter
What is the input to the program? The string
What is the output of the program? The seperated string in bracketed parts
What is the input to each recursive call? The string after the first detected seperator, minus that seperator
What is the output of each recursive call? The first piece of the string before the seperator added to an array as it’s own string


Fibonacci
What is the input to the program? n
What is the output of the program? The Fibonacci result
What is the input to each recursive call? N minus 1
What is the output of each recursive call? N times call to function, with n plus 1 as parameter


Factorial
What is the input to the program? n
What is the output of the program? The factorial result
What is the input to each recursive call? N minus 1
What is the output of each recursive call? N times call to function, with n - 1 as parameter


Find a way out of the maze
What is the input to the program? Command to move
What is the output of the program? The command list to escape the maze
What is the input to each recursive call? The command to move next
What is the output of each recursive call? The next command 


Find ALL the ways out of the maze
What is the input to the program? Command to move
What is the output of the program? All the possible ways to escape the maze
What is the input to each recursive call? Command to move next
What is the output of each recursive call? 4 calls (up, down, left right).


Anagrams
What is the input to the program? The original word
What is the output of the program? A list of all valid words from the word provided
What is the input to each recursive call? The first letter of the string given
What is the output of each recursive call? Call the function with first letter removed.


Organization Chart
What is the input to the program? The org chart
What is the output of the program? The organized org chart
What is the input to each recursive call? An object with all names for the department
What is the output of each recursive call? The supervisor of the department or (if none) all the employees under it


Binary Representation
What is the input to the program? The integer
What is the output of the program? The binary number
What is the input to each recursive call?  The number input divided by 2
What is the output of each recursive call? The modulus result of the number divided by 2 
