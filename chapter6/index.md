# Creating and Using Objects

Classes are blueprints for objects. When they are made, they are new objects based on their blueprints. In fact, the keyword new is used when creating objects.

**Example C# Object Creation:**

```CSharp
class Person {

}

Person p = new Person();
```

In the above example, the new keyword is used to create a new object based on its blueprint, the class Person. As it is C#, and it is a strongly-typed programming language, the type of the object is also Person.

**Example JavaScript Object Creation:**

```CSharp
class Person {

}

let p = new Person();
```

In JavaScript, because it is a loosely-typed programming language, the type is not needed. However, the keywords are the same. class is used to define the class and new is used to create a new object based on the class.

## Constructor Method

In both C\# and JavaScript, what followed the keyword new was Person(). This looks like a function because it is! It is a special kind of method called a constructor.

When an object is created (constructed), a special method named after the class is called.

**Example C# Constructor:**

```CSharp
class Person {

  public Person() {
    // This will be called when the object is created!
  }

}
```

In the above C\# example, the keyword public is also used. Methods, like fields, default to private in C\#. It needs the use of the keyword public to signal that it is public.

In JavaScript, the code would look very similar.

**Example JavaScript Constructor:**

```JavaScript
class Person {

  Person() {
    // This will be called when the object is created!
  }

}
```

## Referring to Itself

In most programming languages, the keyword this is used by classes to refer to themselves. Like with calling methods of classes, a period is used between the keyword and the field or method.

**Example C# this:**

```CSharp
// Create a class
class Person {

  // Create a public Name property
  public string Name;

  // Create a constructor
  public Person(string name) {

    // Pass a value and use it internally
    this.Name = name;
  }

}
```

**Example JavaScript this:**

```JavaScript
class Person {
  // Create a public Name property
  Name;

  // Create a constructor
  Person(name) {

    // Pass a value and use it internally
    this.Name = name;
  }
}
```
