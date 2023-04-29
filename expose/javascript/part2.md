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

13. A returns `'32'` because the number `2` will be converted into a string and
    concatenate `'3'` with `2`. 

    B returns `1` because the operation is subtraction, which will convert the
    string `'3'` into an integer `3`.

    C returns `3` because null is converted into a number with value `0`.

    D returns `'3null'` because `'3'` is a string and `null` will convert into
    string `'null'` when concatenated.

    E returns `4` because `true` is converted into the number `1`.

    F returns `0` because both `false` and `null` are converted into the number
    `0`.

    G returns `'3undefined'` because `undefined` will be converted to the
    string `'undefined'` when concatenated.

    H returns `NaN` because we are trying to subtract `undefined`, which is not
    converted to a number. 

14. A returns `true` because when comparing values of different types, values
    are converted into numbers.

    B returns `false` because the comparison is alphabetical, where the string `'1'` is before `'2'`.

    C returns `true` because the string `'2'` is converted to a number.

    D returns `false` because the operands are different types.

    E returns `false` because the `true` is converted into the number `1`.

    F returns `true` because Boolean(2) returns `true` since 2 is nonzero.

15. The `==` operator will perform the comparison after type conversion, where
    the `===` operator will return false if the operands are different types.

16. ```javascript
    for (let val in statistics) {
        if (val.startsWith('r') || statistics[val] % 2 === 1) {
            console.log(statistics[val]);
        }
    }
    ```

17. The function returns `[ 2, 4, 6 ]`. This function will call the `callback`
    function for each element in the array input, so each value of `array` is
    multiplied by 2.

18. ```javascript
    setInterval(() => {
        let d = new Date()
        let time = d.toLocaleTimeString()
        console.log(time)
    }, 1000)
    ```

19. ```
    1
    4
    3
    2
    ```

