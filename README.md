_printf

In this project, we recreated a mini-verison of the ```printf``` function found in > the ```stdio.h``` library in the C programming language. This function allows > us to print any argument given to the standard output or terminal and similar > printing functions can be found in any programming language. This means we can > print any combinations of strings, intergers, and other different data types. 

Prototype: int _printf(const char *, ...);
Examples

String

    Input: _printf("%s\n", 'This is a string.');
    Output: This is a string.

Character

    Input: _printf("The first letter in the alphabet is %c\n", 'A');
    Output: The first letter in the alphabet is A

Integer

    Input: _printf("There are %i dozens in a gross\n", 12);
    Output: There are 12 dozens in a gross

Decimal:

    Input: _printf("%d\n", 1000);
    Output: 1000

Project Requirements

    All files will be compiled on Ubuntu 14.04 LTS
    Programs and functions will be compiled with gcc 4.8.4 using flags -Wall -Werror -Wextra and -pedantic
    Code must follow the Betty style
    Global variables are not allowed
    Authorized functions and macros:
        write (man 2 write)
        malloc (man 3 malloc)
        free (man 3 free)
        va_start (man 3 va_start)
        va_end (man 3 va_end)
        va_copy (man 3 va_copy)
        va_arg (man 3 va_arg)

Mandatory Tasks

    Write function that produces output with conversion specifiers c, s, and %.
    Handle conversion specifiers d, i.
    Create a man page for your function.

Advanced Tasks

    Handle conversion specifier b.
    Handle conversion specifiers u, o, x, X.
    Use a local buffer of 1024 chars in order to call write as little as possible.
    Handle conversion specifier S.
    Handle conversion specifier p.
    Handle flag characters +, space, and # for non-custom conversion specifiers.
    Handle length modifiers l and h for non-custom conversion specifiers.
    Handle the field width for non-custom conversion specifiers.
    Handle the precision for non-custom conversion specifiers.
    Handle the 0 flag character for non-custom conversion specifiers.
    Handle the custom conversion specifier r that prints the reversed string.
    Handle the custom conversion specifier R that prints the rot13'ed string.
    All above options should work well together.
