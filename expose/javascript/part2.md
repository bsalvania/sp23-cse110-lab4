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
13. 

