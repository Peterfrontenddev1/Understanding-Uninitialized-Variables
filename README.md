# Understanding-Uninitialized-Variables
undefined

In JavaScript if a variable has been declared, but has not been assigned a value, is automatically assigned the value undefined . Therefore, if you try to display the value of such variable, the word "undefined" will be displayed.
When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of undefined.

How do you fix undefined variables in JavaScript?

use const and let . Don't use `var'

use === not ==

Initialize the three variables a, b, and c with 5, 10, and "I am a" respectively so that they will not be undefined.

a should be defined and evaluated to have the value of 6.

b should be defined and evaluated to have the value of 15.
