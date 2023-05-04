### 1. What will happen at line 12 and why? If the code causes an error, explain why. 

Answer: `3` will be printed since the `var` provides the variable as function scope and the length of `prices` is `3`. `i` is defined for the whole funtion and the `for loop` will stop while `i` is equal to `3`. Then `line 12` print the value of `i`.

### 2. What will happen at line 13 and why? If the code causes an error, explain why. 

Answer: `150` will be printed since the `var` provides the variable `discountedPrice` as function scope and it is initialized at the beginning of the `for loop`. 
For the last loop:
```
var discountedPrice = prices[2] * (1 - 0.5);
// discountedPrice = 300 * (1 - 0.5) = 150
```

### 3. What will happen at line 14 and why? If the code causes an error, explain why. 

Answer: `150` will be printed since the `var` provides the variable `finalPrice` as function scope and it is initialized at the beginning of the function but reassigned in every loop of the `for loop`.
For the last loop:
```
// discountedPrice = 300 * (1 - 0.5) = 150
finalPrice = Math. round(discountedPrice * 100) / 100;
// finalPrice = Math.round(150 * 100) / 100 = 150
```

### 4. What will this function return? Give a brief explanation why. If the code causes an error, explain why. 

Answer: it will return `[50, 100, 150]` since `discounted` is defined as an array and the code returns the `discounted`.
```
discounted[0] = 100 * (1 - 0.5) * 100 / 100 = 50
discounted[1] = 200 * (1 - 0.5) * 100 / 100 = 100
discounted[2] = 300 * (1 - 0.5) * 100 / 100 = 150
```

### 5. What will happen at line 12 and why?  If the code causes an error, explain why. (assume this function is being called like the others: `discountPrices([100, 200, 300], 0.5)`).

### 6. What will happen at line 13 and why? If the code causes an error, explain why. 

### 7. What will happen at line 14 and why? If the code causes an error, explain why. 

### 8. What will this function return? Give a brief explanation. If the code causes an error, explain why. 

### 9. What will happen at line 11 and why? If the code causes an error, explain why. 

### 10. What will happen at line 12 and why? If the code causes an error, explain why. 

### 11. What will this function return? Give a brief explanation. If the code causes an error, explain why.

### 12. Given the above Object, write the notation for:  (These should be in your part2.md)
```
A. Accessing the value of the name property in the student object
B. Accessing the value of the Grad Year property in the student object
C. Calling the function for the greeting property in the student object
D. Accessing the name property of the object in the Favorite Teacher property in student
E. Access index zero in the array of the courseLoad property of the student object
```

### 13. Arithmetic
```
A. ‘3’ + 2
B. ‘3’ - 2
C. 3 + null
D. ‘3’ + null
E. true + 3
F. false + null
G. '3' + undefined
H. '3' - undefined
```

### 14. Comparison
```
A. ‘2’ > 1
B. ‘2’ < ‘12’
C. 2 == ‘2’
D. 2 === ‘2’
E. true == 2
F. true === Boolean(2)
```

### 15. Explain the difference between the == and === operators.

### 16. Given the above Object, write a for...in loop that will iterate through it and print out the value of the property if the property starts with the letter r, or if the value of that property is an odd number.  (This should be in a JS file `part2-question16.js`)

### 17. If the function above is called with the following parameters `modifyArray([1,2,3], doSomething)`, what will be the result? Briefly walk through how you arrived at that result. (This should be in your `part2.md`). Here we are passing in a function as a parameter, however we can also return a function from another function just as easily, you're encouraged to play around with callbacks as they are used heavily in frontend JS development. 

### 18. The above program only prints out the time once when executed. Modify this code such that the program prints out the time every second.  (This should be a JS file - `part2-question18.js`)

### 19. What is the output of the above code? (This should be in your `part2.md`)

