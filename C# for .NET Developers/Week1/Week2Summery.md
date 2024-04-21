# Week 2 Summary

## Introduction to C#
* C# is a general-purpose high-level programming language supporting multiple paradigms.
* Intended to be a simple, modern, general-purpose, object-oriented programming language.
* Intended for use in developing software components suitable for deployment in distributed environments.

## History of C# Version
* Designed by Anders Hejlsberg from Microsoft in 2000.
* Approved as an international standard by Ecma in 2002.
* Microsoft introduced C# along with .NET Framework and Visual Studio as closed source.
* A decade later, Microsoft released Visual Studio Code, Roslyn (compiler), and the unified .NET platform, all supporting C#, as free, open-source, and cross-platform.

## C# Code Execution
* Core syntax similar to C, C++, and Java.
  * Semicolons are used to denote the end of a statement.
  * Curly brackets are used to group statements.
  * Variables are assigned using an equals sign, but compared using two consecutive equals signs.
  * Square brackets are used with arrays.

### Example: Hello World in C# 9
```csharp
using System;
Console.WriteLine("Hello, world!");


Alright! Here's your Week 2 content formatted as a README.md using only * for bullet points and # for headers:

markdown
Copy code
# Week 2 Summary

## Introduction to C#
* C# is a general-purpose high-level programming language supporting multiple paradigms.
* Intended to be a simple, modern, general-purpose, object-oriented programming language.
* Intended for use in developing software components suitable for deployment in distributed environments.

## History of C# Version
* Designed by Anders Hejlsberg from Microsoft in 2000.
* Approved as an international standard by Ecma in 2002.
* Microsoft introduced C# along with .NET Framework and Visual Studio as closed source.
* A decade later, Microsoft released Visual Studio Code, Roslyn (compiler), and the unified .NET platform, all supporting C#, as free, open-source, and cross-platform.

## C# Code Execution
* Core syntax similar to C, C++, and Java.
  * Semicolons are used to denote the end of a statement.
  * Curly brackets are used to group statements.
  * Variables are assigned using an equals sign, but compared using two consecutive equals signs.
  * Square brackets are used with arrays.

### Example: Hello World in C# 9
```csharp
using System;
Console.WriteLine("Hello, world!");

## Installing and Configuring Visual Studio
Visual Studio Code, commonly referred to as VS Code, is a source-code editor made by Microsoft.
Built with the Electron Framework.
Available for Windows, Linux, and macOS.

Variable
Variables are identifiers associated with values.
Declared by writing the variable's type and name.
Optionally initialized in the same statement.
Data Type
C# has a unified type system known as Common Type System (CTS).
Reference types
Value types
Operators
C# provides a number of operators.
Arithmetic operators
Comparison operators
Boolean logical operators
Bitwise and shift operators
Equality operators
Operators precedence
Operator precedence determines the grouping of terms in an expression.
Certain operators have higher precedence than others.
Conditional Statements: if, if..else if, switch
The if statement executes a statement only if a provided Boolean expression evaluates to true.
The if-else statement allows choosing between two code paths.
The switch statement selects a statement list based on a pattern match with an expression.
Loops: do..while, while, for, foreach
The for statement executes its body while a specified Boolean expression evaluates to true.
The foreach statement enumerates the elements of a collection and executes its body for each element.
The do statement conditionally executes its body one or more times.
The while statement conditionally executes its body zero or more times.
Jump Statements
Used to transfer control within the program.
Keywords:
break
continue
goto
return
throw
Arrays
An array type is a reference type.
All array types derive from a common base class, System.Array.
Types of Arrays:
Single Dimensional Array
Multi Dimensional Array
Jagged Array
Strings
A string is an object of type String.
Internally, the text is stored as a sequential read-only collection of Char objects.
String Methods
Operations such as concatenation, comparison, getting substring, search, trim, replacement, etc.
Object-Oriented Programming Concepts
C# has direct support for object-oriented programming.
Objects
An object is created with the type as a template and is called an instance of that particular type.
Objects are either references or values.
Classes
Classes are fundamentals of an object-oriented language such as C#.
They serve as a template for objects.
Access Modifiers
Modifiers set the accessibility of classes, methods, and members.
Constructor
A constructor is a special method that is called automatically when an object is created.
Inheritance
Classes in C# may only inherit from one class.
Methods
Methods are functions that group reusable code.
Structure
Classes and structures are similar but have differences.
Classes are reference types, and structs are value types.
