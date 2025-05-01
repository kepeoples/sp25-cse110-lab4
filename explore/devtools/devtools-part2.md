# DevTools - Debugging

1. **What was the bug?**  
   The `num1` and `num2` values were treated as strings, so the `+` operator concatenated them instead of adding them numerically. For example, entering 2 and 3 gave "23" instead of 5.

2. **How would you fix it?**  
   Convert both inputs to numbers before adding:
   ```js
   let result = Number(num1) + Number(num2);
