# Statements and the structure of the program

## What is a statment?

- A statement is a type of instruction that causes the program to perform some action 

- A statement can be a single line of code or a block of code enclosed in curly brackets, but in c++, not all of them end in semicolons

- A statement can be a function call, an assignment, a control flow statement, a jump statement
  
- A statement can be a declaration, an expression, a return statement


## Types of statements
- **Declaration statements**: declaration statement is a statement that introduces a new identifier (e.g., a variable, function, or class) into the program. It specifies the type and name of the identifier, and may also initialize it with a value
  
    ```cpp
    int x;  // declares an integer variable x
    double y = 3.14;  // declares a double variable y and initializes it to 3.14
    ```

- **Jump statements**: a jump statement is a statement that transfers control to another location in the program. There are several types of jump statements in C++:
  
  - **break**: exits a loop or switch statement
  
  - **continue**: skips to the next iteration of a loop
  
  - **return**: exits a function and returns a value to the caller
  
  - **goto**: transfers control to a labeled statement
    ```cpp
    for (int i = 0; i < 5; i++) {
    if (i == 3) break;  // exits the loop when i is 3
    cout << i << endl;
    }
    ```
  
- **Expression statements**: 
- **Compound statements**: 
- **Selection statements** (conditionals): 
- **Iteration statements** (loops): 
- **Try blocks**: 
huh