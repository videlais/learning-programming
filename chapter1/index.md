# Chapter 1: Keywords and Comments

- [Chapter 1: Keywords and Comments](#chapter-1-keywords-and-comments)
  - [Letting Colors Guide You](#letting-colors-guide-you)
  - [Adding Comments](#adding-comments)
  - [Comments and Code](#comments-and-code)

---

Programming languages are languages. They have particular meanings, concepts, and usages that make them different from other programming and even spoken languages. In a very general sense, programming languages can be broken down into two large categories of content: keywords and comments.

Programming is written using certain words (*keywords*) that have particular importance to the language. These have special meaning and are instructions for a computer.

The opposite, in a sense, are comments. Unlike keywords, these are primarily written for humans. They can be instructions, documentation, or just notes for other people. They exist alongside and often appear before or after the use of keywords and help to explain their meaning.

## Letting Colors Guide You

Programming is often written using special text editors for writing code. Examples of these include the program Atom, Sublime Text, and Visual Studio (Code). Each of these uses what is known as syntax highlighting (Links to an external site.). Similar to using Microsoft Word or other programs, colors are used alongside the text to show meaning to a user.

When a text editor like Visual Studio Code understands that a programming language is being used, it will highlight the keywords of that language in special colors. This helps not only visually mark which keywords are being used in a particular file, but also helps developers when writing code check that they are following the rules of the language.

**Example of JavaScript Code:**

```JavaScript
let example = 5;
example += 2;
```

In the above JavaScript example, the keyword let is used. It has special meaning in the programming language JavaScript.

**Example of C# Code:**

```CSharp
public class Example {}
```

In the above C\# example, there are two keywords: `public` and `class`. These each have special meaning in the language.

In both JavaScript and C\# examples, syntax highlighting is used to color-code the keywords of each programming languages.

## Adding Comments

Depending on the programming language, comments can take different forms. In both JavaScript and C\#, however, the forms are the same.

A single-line comment is written starting with two backslashes, `//`. Anything after them till the end of the line are part of the single-line comment.

**Single-Line Comment Example in JavaScript:**

```JavaScript
// This is a single-line comment.
```

Multi-line comments starts with a single backslash and then an asterisk, /*. They end when the pattern is reversed. A multi-line comments ends with an asterisk and a backslash.

**Multi-Line Comment Example in C\#:**

```CSharp
/* This is a multi-line
comment. It can easily run across
multiple lines. All of this is
considered a single comment. */
```

## Comments and Code

It is common to write a comment on one or more lines before the usage of keywords to explain their meaning in code. The comments will be ignored by the computer. It will focus on the code lines following the comments.

**Example of C\# Code with Comments:**

```CSharp
// This creates a variable
int example = 5;
// Change the value of the variable
example = 6;
```
