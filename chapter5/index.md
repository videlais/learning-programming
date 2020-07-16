# Properties and Methods

When discussing fields of objects, some programming languages use the term properties. In a strict sense, however, a property is an aspect of an object that can be used external to the object. It is a field that is accessed through the object itself.

## Public and Private

The fields of an object are either private or public in relation to the class. That is, they can either only be accessed by the class (private) or can be accessed outside of the class (public).

If the language is strongly-typed, like C\#, all fields are defaulted to private access only. In loosely-typed languages, like JavaScript, they default to public.

The keywords public and private mark its access in strongly-typed programming languages.

**Example C# Class with Public Properties:**

```CSharp
class CarClass {
  // Public Color of the car
  public string Color;

  // Public Make of the car
  public string Make;

  // Public Model of the car
  public string Model;
}
```

Normally, JavaScript does not allow private fields. However, in some very recent versions of Node.js and in select web browsers, this is allowed using a hash, `#`, in front of the name of the field.

**JavaScript Private Class Fields Example (Experimental Feature):**

```JavaScript
class CarClass {
  // Private Color
  #Color;
  // Private Make
  #Make;
  // Private Model
  #Model;
}
```

## Classes Containing Functions

Along with variables (fields), classes can also contain functions. Like with variables, the name of these changes when inside a class. They become methods.

A method of a class is a function that is part of a class. It is defined inside of the curly brackets of the class.

Like the difference between strongly-typed and loosely-typed languages, functions defined inside of a class (methods) use either its return type and name or just the name of the method.

**Example JavaScript Class Method:**

```JavaScript
// Define the class Person
class Person {
  // Define the method SayHi()
  SayHi() {
    // Call the method log() of the object console
    console.log("Hi!");
  }
}
```

Unlike with fields, methods default to public access when defined. However, in strongly-typed programming languages, like C\#, they can also use the keyword private and can only be used inside of the class that defines them.

**Example C# Class Method:**

```CSharp
class Person {
  // Define a public method SayHi() that returns nothing (void)
  public void SayHi() {
    // Call the method WriteLine() of the object Console
    Console.WriteLine("Hi!");
  }
}
```

In C\#, however, unlike in JavaScript, the keyword private or public must be used before the name of the method. It must also have a return type.

## Calling Class Methods

As methods are functions inside of a class, they are called via the class in which they are defined. For example, one of the most commonly used methods in all of JavaScript is **log()**. It is part of the object console. Its use is to display data on the "console" (command-line when used in a server context and in a separate window, when used in a web browser.)

The method **log()** is used as part of the object console. As shown in the above JavaScript example, it is used as **console.log()** with a period between the object and the method within it.

Both C\# and JavaScript use this pattern. The object name comes first and then a period. The property (public field) or method name then follows this.

As shown in the C\# version of the same code, its equivalent of **console.log()** is the method **WriteLine()** of its object **Console**. In both cases, there is a period between the object and its field or method usage.
