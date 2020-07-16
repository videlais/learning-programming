# Functions

- [Functions](#functions)
  - [Parts of a Function](#parts-of-a-function)
    - [Return Type](#return-type)
    - [Name](#name)
    - [Parameters](#parameters)
    - [Body](#body)
    - [Return Statement](#return-statement)
  - [Putting Functions into Practice](#putting-functions-into-practice)

---

Code is written, and runs, in a general top to bottom pattern. For example, consider the following code written in JavaScript:

```JavaScript
// Create a variable
let example = 5;
// Change the value of the variable
example = 6;
```

The lines of the code would be run in order, creating the variable and then changing its value.

When many hundreds or even thousands of lines of code are written, this can become hard to figure out for developers. To help with this, code functionality can be broken up into smaller units, functions.

Borrowing with mathematics, functions are sections of code dedicated to a single task. This allows for not only understanding the code, but also in debugging it when a problem goes wrong. They can accept input and provide output.

One way to think about them are tiny programs dedicated to one purpose.

## Parts of a Function

Functions are composed of five different parts:

- Return Type
- Name
- Parameters
- Body
- Return Statement

```CSharp  
/*
  C# Function Example
   - Return Type: int (Integer)
   - Name: Addition
   - Parameters: int x, int y
   - Body: return x + y
   - Return Statement: return x + y
*/
int Addition(int x, int y) {
  return x + y;
}
```

### Return Type

In strongly-typed programming languages, the return type of a function is a data type. This is the type returned from the function. It's output.

### Name

Functions names follow the same rules and naming schemes as variables. They can contain letters, numbers, and the underscore. They cannot contain spaces or other special characters.

### Parameters

Like the tiny programs they are, functions can accept different input. These are its parameters.

In a strongly-typed programming language, each parameter must have its own type. In a loosely-typed programming, only the name of the parameters, as variables, is needed.

### Body

Any code that is part of the function is part of its body.

### Return Statement

The keyword return is used as part of functions to "return" some output. In strongly-typed programming languages, the return statement of the function must match its return type. In loosely-typed programming languages, the return type of the function is defined as part of its return statement.

While some programming languages require the use of the return keyword, in both C\# and JavaScript, this is optional.

## Putting Functions into Practice

Because functions are like tiny programs within a larger one, they can help break up a complicated problem into smaller parts. Each one can then be called when needed and passed data it can work on within itself. When it is done, it can return back to the larger program.Consider the following code that adds numbers together:

**Original JavaScript Example:**

```JavaScript
// Create a variable with the value 2
let x = 2;
// Create a variable with the value 2
let y = 2;
// Create a variable with the combined values of x and y
let z = x + y;
```

In the above code, three variables are used. Two are created with the value of the number 2 and then a third is created with their combined values of 4. What if the values of *x* and *y* were not known? If the result of their addition should always be in the variable *z*, a function could be used here instead.

**Function in JavaScript:**

```JavaScript
/*
  JavaScript Example Function
  - Return Type: (number)
  - Name: Addition
  - Parameters: x, y
  - Body: return x + y
  - Return Statement: return x + y
*/
function Addition(x, y) {
  // Return the result of the addition
  return x + y;
}

// Create a variable with the combined values of two numbers
let z = Addition(2, 2);
```

In the above code, a new function **Addition()** is created in JavaScript. It accepts as its parameters two values, *x* and *y*. Notice that because JavaScript is a loosely-type programming language, the type of the values is not as important. (This was different from the C\# example where int was used in multiple places to mark the type of data being worked on inside the function.)

The new line is the last one. Here, the function is being called. In programming terminology, functions are called when they are used after they are defined. In this case, the function **Addition()** is being called and passed two values.

When a function is being called, the values passed to it becomes its *arguments*. These map to its *parameters*. When it is being defined, they are parameters. When used, when it is being called, the data passed to it are arguments.

The arguments to the function **Addition()** are the numbers 2 and 2. Inside the function, its return statement adds these numbers and then returns the result. This is its output.

While using the same values and performing the same general operations, the use of the function means that now any numbers could be added using the function, making it both more general and easily to understand within a larger structure.
