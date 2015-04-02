# Problem Set 1

Writing, compiling, and debugging programs. Preprocessor macros. C file
structure. Variables. Functions and program statements. Returning from
functions.

## Problem 1.1

 1. What do curly braces (`{` and `}`) denote in C? Why does it make sense to
    use them to surround a function body?
 2. Describe the difference between the literal values `7`, `"7"`, and `'7'`.
 3. Consider the statement `double ans = 10.0 + 2.0 / 3.0 - 2.0 * 2.0`.
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

```c
1. return 0;
2. const char msg[] = MSG;
3. }
4. main(void)
5. int
6. #include <stdio.h>
7. {
8. #define MSG "All your base are belong to us."
9. printf(msg);
```

## Problem 1.5

For each of the following statements, explain why the statement is incorrect
and write a correct version of the statement.

 1. `#include <stdio.h>;`
 2. `int function(void arg) { return arg - 1; }`
 3. `#define MESSAGE = "I think he's talking about the ping pong ball."`

