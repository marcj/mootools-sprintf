# Javascript sprintf for mootools

This is just a small function, that provides almost the same as php's sprintf.

Take a look at the docu of php's sprintf to get more informationen about the possibilities.

# How to Use

```javascript

"Hi %s, you have %d new messages!".sprintf('Peter', 3);
//Hi Peter, you have 3 new messages!

var text = "My name is %s and I'm %s, because I'm %1$s".;
console.log(text.sprintf('Peter', 'holy')); //My name is Peter and I'm holy, because I'm Peter

```

## Possible types:

 - % - a literal percent character. No argument is required.
 - b - the argument is treated as an integer, and presented as a binary number.
 - c - the argument is treated as an integer, and presented as the character with that ASCII value.
 - d - the argument is treated as an integer, and presented as a (signed) decimal number.
 - e - the argument is treated as scientific notation (e.g. 1.2e+2).
 - E - like %e but uses uppercase letter (e.g. 1.2E+2).
 - u - the argument is treated as an integer, and presented as an unsigned decimal number.
 - f - the argument is treated as a float, and presented as a floating-point number.
 - o - the argument is treated as an integer, and presented as an octal number.
 - s - the argument is treated as and presented as a string.
 - x - the argument is treated as an integer and presented as a hexadecimal number (with lowercase letters).
 - X - the argument is treated as an integer and presented as a hexadecimal number (with uppercase letters).

Text Copyright by http://www.php.net/manual/en/function.sprintf.php

## Argument swapping

This function supports argument swapping, which means, you can use a argument as many as you want in the text.
Just use for example following to output the first argument as string again.

```javascript

"Si, glamour is %s, or is it not %1$s?".sprintf('useless');

```

# More information

Please take a look at this page: http://www.php.net/manual/en/function.sprintf.php
to get more information about the possibilities.


# Requirements

 - Mootools core.
 - Mootools more String.Extras repeat. (more/String.Extras)
