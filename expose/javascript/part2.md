<!-- 1. 3;  because var is function scoped and i is still accessible after the loop ends.
2. 150;  Line 13 prints 150 because var is function scoped and discountedPrice is still accessible outside the for loop.
3. 150;  It will print 150 because finalPrice is declared with var and is accessible after the loop.
4. [50, 100, 150];  The function returns [50, 100, 150] because it computes the discounted price for each item, rounds it, and stores it into an array.
5. ReferenceError: i is not defined, because let is block scoped and i is not available outside the for loop.
6. ReferenceError: discountedPrice is not defined, because let is block scoped and discountedPrice is not accessible outside the for loop.
7. 150 as let allows discounted and finalPrice to stay accessible throughout the function.
8. [50,100,150] because it correctly calculates discounted prices, and let allows discounted and finalPrice to stay accessible throughout the function.
9. ReferenceError: i is not defined; Line 11 causes a ReferenceError because i was declared with let inside the for loop and is not accessible outside its block.
10. It prints 3 because length is declared with const in the function scope and holds the value 3.
11. The function returns [50, 100, 150] because it correctly calculates and stores the discounted prices, and using const for arrays still allows modification through push().
12. A: alert(student.name) B: alert(student["Grad Year"]) C: alert(student.greeting()) D: alert(student["Favorite Teacher"].name) E: alert(student.courseLoad[0])
 -->

## Part 2 Answers

1.  **Answer:** `3`; because `var` is function scoped and `i` is still accessible after the loop ends.

2.  **Answer:** `150`; Line 13 prints 150 because `var` is function scoped and `discountedPrice` is still accessible outside the for loop.

3.  **Answer:** `150`; It prints 150 because `finalPrice` is declared with `var` and is accessible after the loop.

4.  **Answer:** `[50, 100, 150]`; The function returns `[50, 100, 150]` because it computes the discounted price for each item, rounds it, and stores it into an array.

5.  **Answer:** `ReferenceError`; `i` is not defined because `let` is block scoped and `i` is not available outside the for loop.

6.  **Answer:** `ReferenceError`; `discountedPrice` is not defined because `let` is block scoped and `discountedPrice` is not accessible outside the for loop.

7.  **Answer:** `150`; because `let` allows `discounted` and `finalPrice` to stay accessible throughout the function.

8.  **Answer:** `[50, 100, 150]`; because it correctly calculates discounted prices, and `let` allows `discounted` and `finalPrice` to stay accessible throughout the function.

9.  **Answer:** `ReferenceError`; Line 11 causes a `ReferenceError` because `i` was declared with `let` inside the for loop and is not accessible outside its block.

10.  **Answer:** `3`; It prints 3 because `length` is declared with `const` in the function scope and holds the value 3.

11.  **Answer:** `[50, 100, 150]`; The function returns `[50, 100, 150]` because it correctly calculates and stores the discounted prices, and using `const` for arrays still allows modification through `push()`.

12.  **Accessing properties and functions:**

- **A:** `alert(student.name)`
- **B:** `alert(student["Grad Year"])`
- **C:** `student.greeting()`
- **D:** `alert(student["Favorite Teacher"].name)`
- **E:** `alert(student.courseLoad[0])`

13. **Arithmetic:**
- **A:** `'32'`
- **B:** `'1'`
- **C:** `3`
- **D:** `'3null'`
- **E:** `4`
- **F:** `0`
- **G:** `3undefined`
- **H:** `NaN`

14. **Comparisons:**
- **A:** `true`
- **B:** `false`
- **C:** `true`
- **D:** `False`
- **E:** `False`
- **F:** `True`

15. `==` checks for value equality with type conversion; `===` checks for value and type equality without conversion.
16. 
```
for (let car in statistics) {
  if (car[0] == 'r' || statistics[car] % 2 != 0) {
    console.log(statistics[car]);
  }
}
```
17. The function returns [2, 4, 6] because it multiplies each element of the input array by 2 using the callback function and stores the results in a new array.
18. 
```
setInterval(function() {
    let date = new Date();
    let time = date.toLocaleTimeString();
    console.log(time);
}, 1000);

```
19. The output is 1, 4, 3, 2 because synchronous code runs first, then setTimeout(0) executes, then after 1 second setTimeout(1000) executes.