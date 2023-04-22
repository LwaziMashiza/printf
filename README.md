PRINTF PROJECT
Description

The printf function sends formatted output to stdout. The _printf()  project was developed by cohort #13 students Lwazi and Maryjane .

The printf() function prints output to stdout, according to format and other arguments passed to printf(). The string format consists of two types of items - characters that will be printed to the screen, and format commands that define how the other arguments to printf() are displayed. Basically, you specify a format string that has text in it, as well as "special" characters that map to the other arguments of printf().

The prototype of this function is: int _printf(const char format, ...);

This means that it has one mandatory format argument, and an extra number of arguments that can be none, or many.

Format of the format string

The format string is a character string starting and ending with double quotes. The format string is composed of zero or more directives; ordinary characters (not %), and conversion specifications, each of which results in fetching zero or more subsequent arguments.

Each conversion specification is introduced by the character % and ends with a conversion specifier. In between there may be (in this order):

Zero or more flags
An optional field width
An optional precision modifier
An optional length modifier

Authorized functions and macros

write (man 2 write) malloc (man 3 malloc) free (man 3 free) va_start (man 3 va_start) va_end (man 3 va_end) va_copy (man 3 va_copy) va_arg (man 3 va_arg)

Authors

Lwazi Luthuli
Maryjane Okafor
Project Started Today 22nd of April, 2023.
