# Classes

As programming has become more complicated, so too have the structures used to write and understand code. So far, variables and functions have been discussed as ways to handle data and perform small tasks. And, for decades, these were the two central concepts used to develop code. Values were saved and changed; functions were used to divided up large projects into smaller tasks.

The introduction of object-oriented programming (OOP) changed how code was viewed. Instead of thinking of data and the tasks associated with them, code could be broken up into objects that related to each other. Following the model of functions allow programming to become more generic, objects allow for modeling parts of code that can be used multiple times.

Whenever possible, re-usability became a central way of thinking about code. Instead of thousands of lines of code, it could be broken up into objects that were hundreds or dozens of lines of code each. Like the transition into using functions, this helps to not only understand the code as smaller parts, but also helps in developing it through needing to write and test less code overall.

## Class Blueprints

The best metaphor for understanding objects is that they are data that is shaped by their blueprints. In programming terminology, this is known as classes.

A class is some code that is used to define an object. In the same way that blueprints define the structure and layout of a building, a class describes how an object is shaped when used.

Like functions, the body of a class is defined by opening and closing curly brackets. Everything "inside" the curly brackets is also part of the class and any future objects.

**Example JavaScript Class:**

```JavaScript
class ExampleClass {

}
```

The keyword class is used in most programming languages to indicate that some code is defining a class. (JavaScript and C\# both use the keyword class for this purpose.)

**Example C# Class:**

```CSharp
class ExampleClass {

}
```

The name of classes follows the same pattern of variables and functions. They can contain letters, numbers, and the underscore. They cannot contain spaces or other special characters.

Unlike some variables, classes should always start with a capital letter. While JavaScript, as a loosely-typed language, will sometimes let developers get away with naming a class as a lowercase letter, C\# will not. Naming classes starting with a capital letter is a good practice

## Containing Variables

Think of a car. It has wheels, a body, and probably other parts. Each of these describe some aspect of the car.

In object-oriented programming terms, anything that describes the object is a field. Think of it like filling out a form. Each "field" would describe some part of the car. These could be its color, make, and model, for example.

Translated into programming terms, these become variables inside the class. These are known as its fields.

**Example C# Car Class:**

```CSharp
class CarClass {
  // Color of the car
  string Color;

  // Make of the car
  string Make;

  // Model of the car
  string Model;
}
```

Depending on if the language is strongly-typed or not, the types of the fields might be different. In C\#, for example, each field needs a type. In JavaScript, they do not need (or can have) one.

**Example JavaScript Car Class:**

```JavaScript
class CarClass {
  // Color of the car
  Color;

  // Make of the car
  Make;
  
  // Model of the car
  Model;
}
```
