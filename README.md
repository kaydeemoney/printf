The printf() function in the C standard library is replicated by _printf, and it is a team project included in the first year curriculum of ALX.

What this project should teach you:



How to use git in a group environment

Using variadic functions in a large-scale undertaking

The intricate details of printf

Finding a good workflow and handling a large number of files

USAGE
Prints a string to the standard output, according to a given format
All files were created and compiled on Ubuntu 14.04.4 LTS using GCC 4.8.4 with the command gcc -Wall -Werror -Wextra -pedantic *.c
Returns the number of characters in the output string on success, -1 otherwise
Call it this way: _printf("format string", arguments...) where format string can contain conversion specifiers and flags, along with regular characters

## Usage * Prints a string in the specified format to the standard output The following command was used to create and compile all files on Ubuntu 14.04.4 LTS: ``{gcc -Wall -Werror -Wextra -pedantic *.c}`}

* If the output string is successful, returns the number of characters; if not, returns -1.

* Refer to it as {{{_printf("format string", arguments...){}{, in which `{{format string{}} may include flags and conversion specifiers.

In addition to typical characters



## Instances



{}{_printf("Hello, main\n"){}} *prints "Hello, Main", then a new line*

The expression {{{_printf("%s", "Hello"){{{ *prints "Hello"*

{{{_printf("This is a number: %d", 98){{{ *prints "This is a number: 98"*



—
