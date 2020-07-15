# Variables

In programming terminology, a variable is a container for different values when writing code. It "contains" data such as numbers, letters, or collection of symbols.

[Diagram of variables with type, name, and value pointed out.]

Variables have three interconnected concepts:

Type
Name
Value
Variable Types
Programming languages are described as strongly or weakly (loosely) typed.

C# is an example of a strongly-typed programming language.
JavaScript is an example of a loosely-typed programming language.
The use of the words "strongly" and "weakly" describes how certain keywords are used in connection to variables. In C#, for example, extra keywords are needed. JavaScript, as a loosely-typed programming language, uses less keywords in regard to variables.

Strongly Typed
In C#, the keyword used first with variables describes its type. This is the kind of values that the variable can hold.

Variables can be thought of buckets. They "hold" values and can be used only with those values. The typeof the bucket is the kind of data that is used with that bucket.

Example of C#:

// Create a variable that can only hold whole number values
int example;
Loosely Typed
JavaScript uses the keywords let and const to mark its variables. Instead of specialized buckets, it uses just two. Values that might change are put in the "bucket" of using let. Variables that will not change are put into the "bucket" of const.

Example of JavaScript:

// Create a variable whose value might change
let example;

// Create a variable whose value will not change
const anotherExample;
Variable Names
After the type or other keyword of a variable is its name. While some programming languages have very strict rules for how variables can be named, there are three general rules nearly all programming languages follow:

A variable name can contain...

the underscore but not other special characters (including spaces!);
numbers (but most do not allow the variable name to start with them); and
both uppercase and lowercase letters.
C# and JavaScript are examples of programming languages that follow the above rules.

Naming Schemes
Large open source projects and organizations often have style guides (Links to an external site.) that explain how variables and other parts of the language such as indentation should be used. Some programming languages like C# even have their own coding conventions (Links to an external site.).

Regardless of their own naming, these documents explain how variable names should be written using two common naming schemes.

camelCase
Many programming languages use what is known as camelCase naming. Because spaces are not allowed in variable names, addition words that are part of the variable's name start with a capital letter after the first word. JavaScript, for example, often uses camelCase naming.

Example JavaScript camelCase Naming:

// Each new word has its first letter capitalized
getElementById();
PascalCase
It is more common to see PascalCase naming in C# than JavaScript. Instead of using a capital letter after the first word, it uses them for every word as part of the variable's name.

Example of C# PascalCase Naming:

// Each letter is capitalized in the variable's name
string CharacterFirstName;
Variable Values
When creating variables, the last thing, left to right, is its value. Following its type and name will be the data (value) of the variable.

A variable's value is influenced by its type. If it is numbers, the variable cannot hold special characters. The same is also true of the reverse: if its type is special characters, it cannot hold number values.

In strongly-type programming languages like C#, type is very important. Trying to put the wrong type of value into a variable will result in an error. In JavaScript, which is a loosely-type programming language, the value will be converted to the new type internally, and the programmer need not worry as much about it.
