0x11. C - printf

The printf project is a collaboration between Onyekachi Uzoma and Paul Akinleye,students of Software Engineering at ALX, were a function named "_printf" imitates the actual "printf" command located in the stdio.h library.
_printf() is a function that performs formatted output conversion
and print data.Where format contains the string that is printed.
As _printf() is variadic function,
it can receives n arguments that replace by n tags
written inside the string.The format tags prototype is the following:
%[flags][length]specifier
If the program runs successfully,
the return value is the amount of chars printed.

0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life

Write a function that produces output according to a format.
Prototype: int _printf(const char *format, ...);
Returns: the number of characters printed (excluding the null byte used to end output to strings)
write output to stdout, the standard output stream
format is a character string. The format string is composed of zero or more directives
 See man 3 printf for more detail. You need to handle the following conversion specifiers:c, s, %

1. Education is when you read the fine print. Experience is what you get if you don't
Handle the following conversion specifiers: d, i

Authors
Onyekachi Uzoma and Paul Akinleye
