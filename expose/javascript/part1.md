<!-- 1. values added: 20  
2. final result: 20  
3. We should not use var because it has no block scope but it has function scope. We should use let or const instead to avoid unexpected bugs.  
4. values added: 20
5. ReferenceError: result is not defined.  This is because let is block scoped and the variable result is not accessible outside the if block where it was declared.
6. TypeError: Assignment to constant variable. This is because variables declared using const are constants and can't be reassigned. Their value can't be changed.
7.  Line 13 is never reached because of the earlier TypeError at line 9.
 -->

## Part 1 Answers

1.  **Answer:** `values added: 20`

2.  **Answer:** `final result: 20`

3.  **Answer:** We should not use `var` because it has no block scope but has function scope. We should use `let` or `const` instead to avoid unexpected bugs.

4.  **Answer:** `values added: 20`

5.  **Answer:** `ReferenceError: result is not defined.`  
This is because `let` is block scoped and the variable `result` is not accessible outside the `if` block where it was declared.

6.  **Answer:** `TypeError: Assignment to constant variable.`  
This is because variables declared using `const` are constants and can't be reassigned. Their value can't be changed.

7.  **Answer:** Line 13 is never reached because of the earlier `TypeError` at line 9.
