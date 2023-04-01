# C - printf

1. Prototype: int _printf(const char *format, ...);
2. Returns: the number of characters printed (excluding the null byte used to end output to strings)
3. write output to stdout, the standard output stream
4. format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
* c
* s
* %
5. You don’t have to reproduce the buffer handling of the C library printf function
6. You don’t have to handle the flag characters
7. You don’t have to handle field width
8. You don’t have to handle precision
9. You don’t have to handle the length modifiers
