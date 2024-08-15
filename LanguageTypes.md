# Types of programming languages

## Table of contents

1. [Compiled vs Interpreted](#compiled-vs-interpreted);
   1. [Compiled languages](#compiled-languages);
      1. [Compiler](#compiler).
   2. [Interpreted languages](#interpreted-languages);
   3. [Scripted languages](#scripted-languages).
      1. [Good and bad points](#good-and-bad-points-about-scripted-languages).
2. [References](#references).

## Compiled vs Interpreted

Generally speaking programming languages may be divides into two categories:

- Compiled languages; and
- Interpreted languages.

A good part of programming languages may have compiled implementations and be interpreted (the language itself isn't necessary compiled or interpreted). But, for terms of simplicity, they are referred this way.
For instance, a food recipe in ancient Greek, in case you do not understand ancient Greek, there are two ways to follow the recipe steps:

1. In case someone have already translated to your language. You (and anyone who understand you language) may read the translated version of the recipe. Think about this version as the compiled version;
2. The other way is having a friend that already understand the ancient Greek version. When you are ready to make the food, this friend will translate and tell the recipe for you. In this case, the friend is the interpreter for interpreted recipe version.

### Compiled languages

Compiled languages ​​are converted directly on the machine into machine code that the processor can execute. As a result, they tend to be faster and more efficient to execute than interpreted languages. They also give the developer more control over some aspects of the hardware, such as memory management and CPU usage.  
Compiled languages ​​require an assembly step – they must first be compiled manually. You must reassemble the program each time you need to make a change.  
Examples of pure compiled languages ​​are C, C++, Erlang, Haskell, Rust, and Go.

#### Compiler

The compiler translates the program into machine language, which is saved on the hard drive as a file with the extension ".o", for example. A linker then links the object code with standard library paths that the program can use and creates an executable image that is also saved on the hard drive, usually as a file with the same name without any extension.

### Interpreted languages

Interpreters go through a program line by line and execute each command. Interpreted languages ​​used to be significantly slower than compiled languages. However, with the development of just-in-time compilation, this gap has been closing.  
Examples of common interpreted languages ​​are PHP, Ruby, Python, and JavaScript.

### Scripted languages

#### Good and bad points about scripted languages

Some good points about scripted languages are:

- The script language allows you to insert various effects, providing a more dynamic and interactive website, with programs, calculators, calendars, calculation tables, current date/time settings, greetings and effects on images by overlaying the mouse;
- Because it is client-side, the code is executed on the person's own equipment, and not on the server;
- Through the script code itself, it is possible to control the browser's behavior in several aspects. For example: opening and closing windows, creating pop-up windows and menus, modifying the browser's dimensions, configuring the status bar, inserting and deleting menus, displaying messages to the user, etc.;
- The ease of form validation, in addition to the possibility of executing instructions in response to user actions, are also advantages;
- The JavaScript code is inserted in a separate file or together with the HTML language commands, facilitating the operation and maintenance of both the page structure and the command lines;
- The scripting language allows the programming of small scripts and larger programs. It also offers many object-oriented possibilities, with complex functions and data structures, and structural elements of the web page, for dynamic access and modification.

Bad points include:

- Easy visibility of source code;
- The script code must be fully downloaded to the browser in order to be executed. Depending on the content and formatting applied, the time factor may be compromised;
- The browser must be configured to interpret script codes, otherwise only the page's structural markup instructions (HTML) will be interpreted.

## References

1. [freecodecamp.org/news/just-in-time-compilation-explained/](https://www.freecodecamp.org/news/just-in-time-compilation-explained/);
2. [freecodecamp.org/portuguese/news/linguagens-de-programacao-interpretadas-x-compiladas-qual-e-a-diferenca/](https://www.freecodecamp.org/portuguese/news/linguagens-de-programacao-interpretadas-x-compiladas-qual-e-a-diferenca/).
