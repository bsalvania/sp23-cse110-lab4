1. The console will output 3, because `i` is a a variable declared using `var` inside a function, meaning it has function scope. Thus, `i` is still within the scope and visible, and is outputted to console. It gets the value of 3 because throughout the for loop, `i` increments up to 3, because `prices` has a length of 3.
2. The console will output 150, because `discountedPrice` is a a variable declared using `var` inside a function, meaning it has function scope. Thus, `discountedPrice` is still within the scope and visible, and is outputted to console. It gets the value of 150 because the last time it is reassigned, it gets the value of `300 * 0.5` which is 150.
3. The console will output 150, because `finalPrice` is a a variable declared using `var` inside a function, meaning it has function scope. Thus, `finalPrice` is still within the scope and visible, and is outputted to console. It gets the value of 150 because the last time it is reassigned, it gets the value of `Math.round(150 * 100) / 100` which is 150.
4. The function will return `[50, 100, 150]` because `discounted` is witin scope the for loop causes every integer in the given array to basically reduce by half of its value, and pushes that halved value to `discounted`, the one that is returned.
5. The code causes an error because `i` is declared using `let` and thus has block scope. Line 12 is outside of that block, so, so `i` is seen as not defined, and an error occurs.
6. The code causes an error because `discountedPrice` is declared using `let` and thus has block scope. Line 13 is outside of that block, so `discountedPrice` is seen as not defined, and an error occurs.
7. The console will output 150, because `finalPrices` is within the same block scope as line 14, thus it can successfully retrieve its value and output it.
8. The function will return `[50, 100, 150]` since `discounted` is still within scope and because the for loop causes every integer in the given array to basically reduce by half of its value, and pushes that halved value to `discounted`, the one that is returned.
9. The code causes an error because `i` is not within the scope of line 11, it was declared using `let` for the for loop, and since line 11 is outside the for loop, the code causes an error.
10. The console will output 3, because `length` was defined to have a value of 3, and it was declared in the same scope that line 12 is at. Additionally, `length` was never attempted to be reassigned, so no errors occur.
11. The function will return `[50, 100, 150]` since `discounted` is still within scope and is never reassigned, values are added to it. Furthermore, the for loop causes every integer in the given array to basically reduce by half of its value, and pushes that halved value to `discounted`, the one that is returned.
12. Notation
    1.  `student.name`
    2.  `student["Grad Year"]`
    3.  `student.greeting()`
    4.  `student["Favorite Teaacher"].name`
    5.  `student.courseLoad[0]`
13. Arithmetic
    1.  `32`: The 2 gets converted to a string, and '3' and '2' concatenated makes '32'. The `+` is used to concatenate strings in this case.
    2.  `1`: The 3 gets converted to an integer, and 3 - 2 = 1. The `-` is used to perform numeric subtraction.
    3.  `3`: null gets converted to a 0 to do numeric addition, and 3 + 0 = 3.
    4.  `3null`: null gets converted to a string to do concatenation, and '3' concatenated with 'null' is '3null'.
    5.  `4`: true gets converted to 1 to do numeric addition, and 1 + 3 = 4.
    6.  `0`: false and null both get converted to 0 to do numeric addition, 0 + 0 = 0.
    7.  `3undefined`: undefined gets converted to a string to do concatenation, and '3' concatenated with 'undefined' is '3undefined'.
    8.  `NaN`: undefined gets converted to NaN, which is not a number, and thus NaN is returned because subtraction cannot be performed.
14. Comparison
    1.  `true`: 2 gets converted to an integer to do integer comparison, and 2 is greater than 1.
    2.  `false`: Dictionary comparison, 2 is not less than 1, so false is returned.
    3.  `true`: 2 gets converted to an integer, and 2 does equal 2.
    4.  `false`: Uses strict equality, and an integer and a string are different types, so false.
    5.  `false`: true gets converted to 1, and 1 does not equal 2.
    6.  `true`: `Boolean(2)` converts 2 to true, and thus they become the same type. And true does equal true.
15. `==` is equality and compares if 2 values are equal and if they are not of the same type, then JavaScript will convert the values to numbers. `===` is strict equality and compares if two values are of the same type and if they are, then check if the values are equal. Basically, `==` does type conversion and `===` does not do type conversion.
16. Check .js file
17. The result will be `[2, 4, 6]`. First, `modifyArray` creates a new empty array. Then, in the for loop, each number in the given array is input into the `doSomething` function, which doubles the value of the number, and then that number is inserted into the new array. When all the values of the given array has been visited, the new array gets returned, which is the original array except every value is now doubled.