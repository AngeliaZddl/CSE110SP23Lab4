### 1. What is printed by line 9? If the code returns an error, explain why. 

Answer: `values added:  20`

### 2. What is printed by line 13? If the code returns an error, explain why. 

Answer: `final result:  20`

### 3. What is printed by line 9? If the code returns an error, explain why.

Answer: `values added:  20`

### 4. What is printed by line 13? If the code returns an error, explain why.

Answer: return an error that 
```
Process exited with code 1
Uncaught ReferenceError ReferenceError: result is not defined
``` 
since `let` declares the variable as block scope, which shows that `result` is only defined in `if (add)`. 

### 5. What is printed by line 9? If the code returns an error, explain why.

Answer: return an error that 
```
Process exited with code 1
Uncaught TypeError TypeError: Assignment to constant variable.
``` 
since `const` provides the variable the same scope as `let` and declares it as a constant that cannot be reassigned after it is assigned for the first time.

### 6. What is printed by line 13? If the code returns an error, explain why. 

Answer: return an error that 
```
Process exited with code 1
Uncaught TypeError TypeError: Assignment to constant variable.
``` 
(From the question 5) the code cannot execute the `line 9` so will stop there and not proceed to the `line 13`.