1. Line 12 will print `3` because the value of `var` variable `i`
   has can be accessed due to its function scope and will terminate from the
   for loop condition when `i` increments to a value greater than or equal
   to the length of `prices`, i.e. a value of 3.

2. Line 13 will print `150` because `discountedPrice` is a var
   variable, meaning it has function scope. In the last iteration of the for
   loop, `i` will be 2, which means the right side of the assignment of
   `discountedPrice` will be equal to 300 * (1 - 0.5) since discount is
   0.5. Thus, the program prints 150.

3. Line 14 will print `150` because `finalPrice` is also a var-declared
   variable, so it has function scope. In the function, `finalPrice` is
   assigned to `discountedPrice` rounded to the nearest hundredth. Thus, 150
   rounded to the nearest hundredth is 150.

4. This function will return an array `[ 50, 100, 150 ]`. As illustrated via
   print statements in the previous questions, the for loop will calculate the
   discounted price for each element in the `prices` array then push the values
   to an array and returns it.

5. The program throws an error because `i` was declared with `let` which limits
   the scope to the block it was declared in. The print statement is not within
   the scope of inside the for loop, which causes an error.

6. The program throws an error for the same reason as question 5,
   `discountedPrice` was declared with `let` inside of the for loop block, so
   it is inaccessible outside of that scope.

7. `finalPrice` is declared in the body of the function with `let`, meaning the
   scope is for the entire function. Therefore, we print the final value of
   `finalPrice` in the for loop after it exits.

8. This function will return the same thing as question 4 `[ 50, 100, 150 ]`
   since it has the same functionality.

9. The program throws an error because the print statement is outside of the
   for loop and tries to print `i` which was declared with `let`, meaning the
   scope is limited to inside the for loop. 

10. Line 12 will print `3` because it prints the value of `length` which was
    declared with `const`, meaning that the value of the variable can not be
    reassigned, which never happens.

11. The function returns `[ 50, 100, 150 ]` for the same reason as in question
    4 since the values calculated with the discount is the same after rounding.

12. ``` 
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
    ```

13. A returns '32' because 

