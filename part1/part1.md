## Part 1a. 
1. values added: 20
2. final result: 20
3. values added: 20
4. Code returns an error. "let" only declares variables within the scope of the code block it's in. The program tries to access "result" outside of the code block it's declared in.
5. Code returns an error. Variables declared with const cannot be reassigned. The code tries to reassign it.
6. Code returns an error for same reason as above.

## Part 1b.
1. 3 is printed to the console
2. 150 is printed to the console
3. 150 is printed to the console
4. It returns an array [50, 100, 150]. The function takes an array of values and a discount, applies the discount to each element in the array, and returns a new array with the discounted prices. 
5. Returns an error. i is defined in the scope of the for loop and line 12 attempts to access it outside of its scope.
6. Returns an error. discountedPrice is defined in the scope of the for loop and line 13 attempts to access it outside of that scope.
7. 150 is printed to the console
8. The function returns the array [50, 100, 150]. It takes an array of values and a discount, applies the discount to each element in the array, and returns a new array with the discounted prices.
9. The code never gets to line 11 because attempting to reassign the constant variable "discounted" on line 7 throws an error. If the code were to get to line 11, it would also throw an error becuase i is declared with let which only allows the variable to be accessed within the scope of the for loop.
10. 3 is printed to the console
11. The function returns [50, 100, 150]. It performs the same funtion as the previous versions of the function. No errors are thrown because no variables are accessed outside of their scope and no constant variables are reassigned. 
12. Object Notation
    1. (a) student.name
    2. (b) student['Grad Year']  
    3. (c) student.greeting()
    4. (d) student['Favorite Teacher'].name
    5. (e) student.courseLoad[0]
13. Arithmetic
    1. (a) '32' - Integers map to exact string representation
    2. (b) 1 - Numeric conversion happens in mathematical expressions
    3. (c) 3 - Numeric conversion in math expression. null maps to 0
    4. (d) '3null' - null maps to 'null' as a string
    5. (e) 4 - true maps to 1 as an integer
    6. (f) 0 - Both false and null map to 0 as integers
    7. (g) '3undefined' - Concatination with a string converts undefined to a string.
    8. (h) NaN - undefined maps to NaN as an integer 
14. Comparison
    1. (a) true - strings become integers in comparisons with an integer, '2' becomes 2
    2. (b) false - two strings are compared lexigraphically. 2 is lexigraphically greater than 12 because 2 comes before 1
    3. (c) true - the string is compared as its integer representation
    4. (d) false - === is a strict equality check, so there is no type conversion
    5. (e) false - true maps to 1 as an integer
    6. (f) true - Boolean(2) returns true, because 2 is a nonzero integer. Therefore === is comparing true === true.
15. The == operator converts types if two different types are being compared. === does not convert types and only returns true if both the type and value of the items being compared are equal.
17. The result is an array [2,4,6]. The array [1,2,3] is sent along with a reference to the doSomething function to the modifyArray function, which takes each element in the array, calls the doSomething function on it (multiplies it by 2), then pushes the result to a new array. The result is an array where each element is doubled.
19. 1 4 3 2 