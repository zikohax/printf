# MEKKAOUI Zakaria and LAHRACHE Abdelghafour - Custom printf() Project

The custom printf() project is a collaborative effort by MEKKAOUI Zakaria and LAHRACHE Abdelghafour, both students of the ALX Software Engineering Programme at Holberton School. The main objective of this project is to create a function named "_printf" that emulates the behavior of the standard "printf" function found in the stdio.h library. This custom _printf() function incorporates some of the fundamental features and functionalities available in the manual 3 of the original "printf".

The _printf() function is designed to handle formatted output conversion and print data accordingly. Its prototype is defined as follows:

```c
int _printf(const char *format, ...)
```

The **format** parameter contains the string that is to be printed. Being a variadic function, _printf() can receive a variable number of arguments that replace the corresponding format tags within the string.

The format tag prototype follows the standard format specification:

```c
%[flags][width][.precision][length]specifier
```

With MEKKAOUI Zakaria and LAHRACHE Abdelghafour's implementation, the custom _printf() function can handle various format specifiers to format and print the supplied data effectively.
