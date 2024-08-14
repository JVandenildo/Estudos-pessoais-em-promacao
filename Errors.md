# Errors and Bugs

The first bug was encountered in 09/09/1947 by computer scientist [Grace Hopper](https://en.wikipedia.org/wiki/Grace_Hopper). She found a moth on the computer Mark II log books. However, the term, as an technical error, is way back on [1878 with Thomas Edison](https://spectrum.ieee.org/did-you-know-edison-coined-the-term-bug).

## Table of contents

1. [Compile-time errors](#compile-time-errors);
2. [Link-time errors](#link-time-errors);
3. [Run-time errors](#run-time-errors);
4. [Logical errors](#logical-errors);
5. [References](#references).

## Compile-time errors

When writing programs, the compiler is the first line of defense against bugs and errors. There are two kinds of compile-time errors:

1. **Syntax error**: this kind of error occur when any language's syntax rule is violated. Some examples are:
   - Semicolon missing (`;`);
   - Any kind of closing brackets missing (`)`, `}`, `]`).
2. **Data type error**: occurs when the data types are not properly matching. Some common examples are:
   - Forgetting the data type declaration;
   - Storage a variable of the wrong type.

## Link-time errors

A link-time, or linker error, occur when the executable for the program cannot be created. This happens when the linker can't comine all the object files into an executable program.

## Run-time errors

An error that occurs after successful execution of the program is called a run-time error. This may happen when excessive memory is used.

## Logical errors

Errors that return an unexpected output, but doesn't seem to contain an error, are called logical errors. These errors are common between beginners and normally are the most difficult to correct.
Logical errors depend exclusively on the programmer's logical thought. Some commons example are:

- program logic is flawed;
- some "silly" mistake inside a `if` statement or block.

Note that logical errors do not have warning messages. Sometimes programmers may use a process called [test-driven development (TDD)](https://en.wikipedia.org/wiki/Test-driven_development), a way to give the logical errors the warning messages and not headaches.

## References

1. [en.wikipedia.org/wiki/Test-driven_development](https://en.wikipedia.org/wiki/Test-driven_development);
2. [codecademy.com/resources/docs/cpp/errors](https://www.codecademy.com/resources/docs/cpp/errors)
