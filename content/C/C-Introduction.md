---
title: 00 - Introduction
---

## Overview

Welcome to the world of C programming! C is one of the oldest and most influential programming languages, serving as the foundation for many modern languages such as C++, Java, and Python. C is a low-level programming language, which doesn't mean it is weak; in fact, it is quite powerful. The term "low-level" refers to its close interaction with the computer's hardware, allowing you to manage memory and system resources directly. This makes C incredibly fast and efficient, ideal for developing operating systems, embedded systems, and other performance-critical applications.

## Why Learn C?

- **Performance**: C is renowned for its speed and efficiency, making it ideal for performance-critical applications.
- **Low-Level Access**: C allows direct manipulation of memory through pointers, giving you granular control over hardware resources.
- **Foundation**: Learning C provides a comprehensive understanding of how computers operate at a fundamental level, laying the groundwork for mastering more complex programming languages and concepts.

## Setting Up Your Environment

To start coding in C, you'll need to set up your development environment. C is a compiled language, meaning you'll require a compiler to convert the source code you write into machine code (the binary pattern of ones and zeroes that the machine understands).

### 1. Install a C Compiler

A C compiler translates your C code into machine code that the computer can execute. Popular options include:

- **[GCC (GNU Compiler Collection)](https://sourceforge.net/projects/mingw/)**: Available on Windows, macOS, and Linux via MinGW. We recommend you watch this [video tutorial](https://youtu.be/GxFiUEO_3zM) to set it up.
- **Online Compilers**: Websites like [Replit](https://replit.com/), [Codepad](http://codepad.org/), and [Ideone](https://ideone.com/) allow you to code in C directly in your browser without any installation.

### 2. Install a Text Editor or IDE

While you can write C code in any text editor, using an Integrated Development Environment (IDE) can greatly enhance your coding experience by providing helpful features like syntax highlighting, code completion, and debugging tools. Popular options include:

- **[Visual Studio Code](https://code.visualstudio.com/)**: A powerful and widely-used code editor that supports C through extensions.
- **[Code::Blocks](http://www.codeblocks.org/)**: A free, open-source IDE specifically designed for C, C++, and Fortran.
- **[CLion](https://www.jetbrains.com/clion/)**: A paid, professional-grade IDE from JetBrains, with extensive support for C and C++.

## Your First C Program

Let's write a simple "Hello, World!" program in C.

> [!example] Creating Your First C Program
>
> 1. **Create a New File**: Create a new file named `hello.c` and save it in your `Downloads` folder.
> 2. **Write the Code**: Copy and paste the following code into `hello.c`:
>
>    ```c
>    #include <stdio.h>
>
>    int main() {
>        printf("Hello, World!\n");
>        return 0;
>    }
>    ```
>
> 3. **Open Terminal in VS Code**: Open the terminal in Visual Studio Code by pressing `Ctrl + \``. Ensure you are in the same directory as the `hello.c`file. If you're not, change to the`Downloads`directory by typing`cd Downloads` and pressing Enter.
>
>    > **Tip**: Using the terminal is a critical skill in programming. To learn more about using the terminal in Visual Studio Code, check out this [guide](https://code.visualstudio.com/docs/terminal/getting-started#:~:text=Start%20VS%20Code%20and%20open,Bash%2C%20PowerShell%2C%20or%20Zsh).
>
> 4. **Compile the Code**: Type `gcc hello.c -o hello` in the terminal.
>
>    - `gcc` is the compiler.
>    - `hello.c` is the source file.
>    - `-o hello` tells the compiler to output the executable file as `hello`.
>
>    Press Enter to execute the command. If the compilation is successful, the terminal will return to the prompt without any errors.
>
> 5. **Run the Program**: Type `./hello` in the terminal and press Enter.
>
>    You should see the output:
>
>    ```
>    Hello, World!
>    ```
>
>    Congratulations! You have successfully compiled and run your first C program.

<!-- I am not sure when to tell them to learn terminal I don't want to diverge too much from the main activity and to start running code because then they will start to get tired and bored. I want then to get excited as they see progress -->

By following these steps, you've created, compiled, and executed your first C program. As you continue to learn C, you'll dive into more advanced topics such as variables, control structures, functions, and pointers, which will help you build more complex and powerful programs.  
