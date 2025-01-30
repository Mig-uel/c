## Chapter 1: What is C programming?

- The C Program you write is called the source code.
- The source code is saved in a file with a .c extension.
- A compiler is a program that translates the source code into machine code.
- Computers are made up of nothing more than a series of switches that can be turned on or off.
- Computers must be given instructions in binary code.
- The prefix bi- means two and the two states of electricity are called binary states.

- An error in a program is called a bug.
- The process of finding and fixing errors is called debugging.

## Chapter 2: How do I get started?

- First glimpse of a C program:

```c
#include <stdio.h>

main() {
  printf("This C stuff is easy!\n");

  return 0;
}
```

- The #include directive tells the compiler to include the contents of the file stdio.h in the program.
- The main() function is the starting point of every C program.
- Each program must have one and only one main() function.
- The printf() function is used to display output on the screen.
- The return statement is used to return a value from the main() function.

- Functions vs commands:

  - A function is a named block of code that performs a specific task.

  ```c
  int add(int a, int b) {
    return a + b;
  }
  ```

  - A command is a built-in instruction that tells the computer to perform a specific task.

  ```c
  printf("Hello, World!\n");
  ```

- The statement `#include <stdio.h>` is needed in almost every C program. It helps with printing and getting data.
- Kinds of data:

  - Integers: whole numbers.
  - Floating-point numbers: numbers with a decimal point.
  - Characters: single letters or symbols.
  - Strings: sequences of characters.

### C Characters

- A C character is any single character that your computer can represent.
- Your computer knows of 256 different characters.
- The ASCII character set is a standard that assigns a number to each character.
- Every letter, number, symbol, and space is a character to C.
- Only one character can be stored in a single apostrophe.
- A group of characters is called a string.
- A string is stored in double quotes.

### Numbers in C

- Numbers take on many different sizes and shapes in C.
- Whole numbers are called integers.
- Integers can be positive or negative.
- Integers can be short, long, or regular.
- Floating-point numbers have decimal points.
- Floating-point numbers can be positive or negative.
- Floating-point numbers can be short, long, or regular.
- Never begin a number with a zero. It will be interpreted as an octal number (base 8) or a hexadecimal number (base 16).
- Internally, C stores integers differently than floating-point numbers.
