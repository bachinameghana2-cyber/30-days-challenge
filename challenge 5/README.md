Algorithm

1. Start
2. Declare the required variables.
3. Display the menu:
   1. Linear Equation
   2. Factorial
   3. Quadratic Equation
   4. Exit
4. Read the user's choice.
5. If choice = 1:
   a. Read a and b.
   b. If a != 0, calculate x = -b/a and display x.
   c. If a = 0 and b = 0, display "Infinitely many solutions".
   d. Otherwise, display "No solution".
6. If choice = 2:
   a. Read n.
   b. If n is between 0 and 12, initialize fact = 1.
   c. Use a for loop to calculate the factorial.
   d. Display the factorial.
   e. Otherwise, display "Invalid input".
7. If choice = 3:
   a. Read a, b, and c.
   b. If a = 0, display "Not a quadratic equation".
   c. Otherwise, calculate D = b*b - 4*a*c.
   d. If D > 0, calculate and display two distinct real roots.
   e. If D = 0, calculate and display two equal real roots.
   f. If D < 0, display "No real roots".
8. If choice = 4, exit the program.
9. If the choice is invalid, display "Invalid choice".
10. Repeat the menu using a do-while loop until the user chooses Exit.
11. Stop
