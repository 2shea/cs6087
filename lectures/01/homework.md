# Problem Set 1

Writing, compiling, and debugging programs. Preprocessor macros. C file
structure. Variables. Functions and program statements. Returning from
functions.

## Problem 1.1

 a. What do curly braces (`{` and `}`) denote in C? Why does it make sense to
    use them to surround a function body?
 b. Describe the difference between the literal values 7, "7", and '7'.
 c. Consider the statement `double ans = 10.0 + 2.0 / 3.0 - 2.0 * 2.0`.
    Rewrite this statement such that the value assigned to `ans` is `11.0`.

## Problem 1.2

Consider the statement:

    double ans = 18.0 / squared(2 + 1);

For each of the four versions of a macro `squared` provided below, write the
corresponding value of `ans`:

 1. `#define squared(x) x * x`
 2. `#define squared(x) (x * x)`
 3. `#define squared(x) (x) * (x)`
 4. `#define squared(x) ((x) * (x))`

## Problem 1.3

Using your preferred text editor, write the "Hello, world!" program described
in the lecture, compile it, and execute it. Copy and paste the output,
showing:

 * the command used to compile your program,
 * the command used to execute your program (using `gdb`), and
 * the output of your program.

## Problem 1.4

The following lines of code, when particularly arranged, form a correct C
program that outputs the message, "All your base are belong to us." Write out
the proper arrangement (specifying order of line numbers is sufficient) for
this code to compile and execute without warnings or errors:

   !c
   return 0;
   const char msg[] = MSG;
   }
   main(void)
   int
   #include <stdio.h>
   {
   #define MSG "All your base are belong to us."
   printf(msg);

## Problem 1.5

For each of the following statements, explain why the statement is incorrect
and write a correct version of the statement.

 a. `#include <stdio.h>;`
 b. `int function(void arg) { return arg - 1; }`
 c. `#define MESSAGE = "I think he's talking about the ping pong ball."`

