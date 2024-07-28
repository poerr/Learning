# 1. Variables & Variable types

---

What are variables? Simply put, they store values that we want to work with in our code. For example, we may have an application where we want to remember and store some value our user put in and use that value later in code. This is what variables are for. We would also use them to store a result of some function we executed and in general, they are the core building block of programming.

Depending on what value we want to store, there are different types of variables. Maybe we want to store an integer or a decimal value, or rather we want to remember a certain string or a character. For every one of these there is a defined type which we would use to represent the type of our variable.

## Variable types

Basic variable types in C programming language (and many more others) are:
- Integer - they represent whole numbers (natural numbers)
> `int x = 5;`
- Float - represents floating point numbers (single precision)
> `float y = 3.14f;`
- Double - floating-point numbers (double precision)
> `double z = 3.14159;`
- Short - short integer numbers 
> `short s = 100;`
- Long - long integer numbers
> `long l = 1000000L;`
- Unsigned Integer - non-negative integer numbers
> `unsigned int = 123;`
- Boolean - values _true_ or _false_
> `bool condition = true;`
- Char - represents a single character
> `char c = "p";`

And many more, but we will stick to these ones for now...

Difference between them (other than the type of value they can hold) is how much memory does each one of them take up:
- int - 4 bytes
- float - 4 bytes
- double - 8 bytes
- char - 1 byte
- short 2 bytes
- long - 4 bytes on 32-bit and 8 bytes on 64-bit systems
- unsigned int - 4 bytes
- bool - 1 byte

## Some basic functions we will be using

Standard functions we will be working with:
`prinf` - used to print some text on the command line
> int x = 5;
>
> printf("The number is %d!", x);

`scanf` - used to take input from the console that the user will be typing in
> int x;
>
> scanf("%d", &x);

These are some examples of their usage. You may be wandering what does '%d' stand for?
These are format specificators. In the above examples we want to print out an `int` value and take input of `int` value. There are other format specifiers, such as:
`%c` - `char`
`%u` - `unsigned` value types
`%f` - `float`
`%lf` - `double`

## Exercises

**Exercise 1:** Let the user input one int value and print that value to the power of 3.
**Exercise 2:** User inputs the radius of the circle, and your job is to calculate the area and circumference of the circle and print it out to the console.
**Exercise 3:** The user inputs 3 numbers. Multiply them all and print it out to the console. Also do the same with addition.

**Link for setting up the environment:** [text](https://code.visualstudio.com/docs/cpp/config-mingw)