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
## Hello World in C#
\`\`\`csharp
using System;
Console.WriteLine("Hello, world!");
\`\`\`

## Installing and Configuring Visual Studio
* Visual Studio Code (VS Code) is a source-code editor by Microsoft.
* Built with the Electron Framework.
* Available for Windows, Linux, and macOS.

## Variable
* Variables are identifiers associated with values.
* Declared by writing the variable's type and name.
* Optionally initialized in the same statement.

## Data Type
* C# has a unified type system known as Common Type System (CTS).
  * Reference types
  * Value types

## Operators
* Arithmetic operators
* Comparison operators
* Boolean logical operators
* Bitwise and shift operators
* Equality operators
* Operators precedence
  * Certain operators have higher precedence than others.

## Conditional Statements
### if
Executes a statement only if a provided Boolean expression evaluates to true.
### if..else if
Allows choosing between two code paths.
### switch
Selects a statement list based on a pattern match with an expression.

## Loops
* do..while: Conditionally executes its body one or more times.
* while: Conditionally executes its body zero or more times.
* for: Executes its body while a specified Boolean expression evaluates to true.
* foreach: Enumerates the elements of a collection and executes its body for each element.

## Jump Statements
* Used to transfer control within the program.
  * break
  * continue
  * goto
  * return
  * throw

## Arrays
* An array type is a reference type.
* All array types derive from a common base class, `System.Array`.
  * Single Dimensional Array
  * Multi Dimensional Array
  * Jagged Array

## Strings
* A string is an object of type `String`.
* Internally, the text is stored as a sequential read-only collection of `Char` objects.
* String Methods
  * Concatenation
  * Comparison
  * Substring
  * Search
  * Trim
  * Replacement

## Object-Oriented Programming Concepts
### Objects
* Created with the type as a template.
* Called an instance of that particular type.
* Either references or values.

### Classes
* Serve as a template for objects.

### Access Modifiers
* Set the accessibility of classes, methods, and members.

### Constructor
* A special method called automatically when an object is created.

## Inheritance
* Classes in C# may only inherit from one class.

## Methods
* Functions that group reusable code.

## Structure
* Classes and structures are similar but have differences.
  * Classes are reference types.
  * Structs are value types.
