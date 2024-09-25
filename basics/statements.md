# Statements and the structure of the program

## What is a statment?

- A statement is a type of instruction that causes the program to perform some action 

- A statement can be a single line of code or a block of code enclosed in curly brackets, but in c++, not all of them end in semicolons

- A statement can be a function call, an assignment, a control flow statement, a jump statement
  
- A statement can be a declaration, an expression, a return statement


## Types of statements
- **Declaration Statements**:  declaration statement is a statement that introduces a new identifier (e.g., a variable, function, or class) into the program.
It specifies the type and name of the identifier, and may also initialize it with a value.

```cpp
int x;  // declares an integer variable x
double y = 3.14;  // declares a double variable y and initializes it to 3.14
```

- **Jump Statements**: jump statement is a statement that transfers control to another location in the program.
There are several types of jump statements in C++:
Break Statement
The break statement exits a loop or switch statement.

```cpp
for (int i = 0; i < 5; i++) {
    if (i == 3) break;  // exits the loop when i is 3
    cout << i << endl;
}
```

- **Continue Statement**
The continue statement skips to the next iteration of a loop.

```cpp
for (int i = 0; i < 5; i++) {
    if (i == 3) continue;  // skips to the next iteration when i is 3
    cout << i << endl;
}
```

- **Return Statement**:
The return statement exits a function and returns a value to the caller.

```cpp
int add(int x, int y) {
    return x + y;  // returns the sum of x and y
}
```

- **Goto Statement**:
The goto statement transfers control to a labeled statement.

```cpp
goto label;  // transfers control to the labeled statement
label: cout << "Hello, world!" << endl;
```

- **Expression Statements**: expression statement is a statement that consists of an expression followed by a semicolon.cIt is used to evaluate an expression and discard its result.

```cpp

x = 5;  // assigns 5 to x
y = x * 2;  // evaluates the expression x * 2 and assigns the result to y
cout << "Hello, world!" << endl;  // evaluates the expression and prints to the console
```

- **Compound Statements**: compound statement is a statement that consists of a sequence of statements enclosed in curly brackets {}.cIt is used to group multiple statements together to form a single statement.

```cpp
{
    int x = 5;
    int y = x * 2;
    cout << "The result is: " << y << endl;
}
```

- **Selection Statements (Conditionals)**:
A selection statement is a statement that selects one of two or more alternative paths of execution based on a condition. It is used to control the flow of the program based on a condition.

```cpp
if (x > 5) {
    cout << "x is greater than 5";
} else {
    cout << "x is less than or equal to 5";
}

switch (x) {
    case 1:
        cout << "x is 1";
        break;
    case 2:
        cout << "x is 2";
        break;
    default:
        cout << "x is neither 1 nor 2";
}
```

- **Iteration Statements (Loops)**: iteration statement is a statement that repeats a sequence of statements until a condition is met. It is used to repeat a set of statements until a condition is satisfied.

```cpp
while (x < 5) {
    cout << "x is " << x << endl;
    x++;
}

for (int i = 0; i < 5; i++) {
    cout << "i is " << i << endl;
}

do {
    cout << "x is " << x << endl;
    x++;
} while (x < 5);
```

- **Try Blocks**
A try block is a statement that encloses a sequence of statements that may throw an exception. It is used to catch and handle exceptions that may occur during the execution of a sequence of statements.

```cpp
try {
    int x = 5 / 0;  // throws a division by zero exception
} catch (const std::exception& e) {
    cout << "Caught an exception: " << e.what() << endl;
}

try {
    File file("example.txt");  // may throw a file not found exception
} catch (const std::exception& e) {
    cout << "Caught an exception: " << e.what() << endl;
}
```

# Functions and the _main_ functions

- A function is a collection of statements 
