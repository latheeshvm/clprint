# clprint

A Python package that adds color to your print statements.

Colors ( 5 )
**`red -> print_r`** **`blue -> print_b`** **`green -> print_g`** **`yellow -> print_y`** **`purple -> print_p`**

## Installation 🚀

To install clprint, run the following command:

```bash
pip install clprint
```

## Usage ⚡️

Import the package in your Python script:

```bash
from clprint import * # imports everything - recommended
```

or

```bash
import clprint as cl # cl.print_r("Hello")
```

or

```bash
from clprint import print_r # print_r("Hello")
```

## Printing in different colors ✨

Use the following functions to print in different colors:

```bash
print_r("Hello") # to print in red
print_g("Hello")  # to print in green
print_b("Hello")  # to print in blue
print_y("Hello")  # to print in yellow
print_p("Hello") # to print in purple
```

## Adding a label ✨

To add a label to your print statement, pass the label argument to the print function:

```bash
print_r("Hello", label="My Label")
```

This will print the label in square brackets before the text:

```bash
[My Label] Hello
```

## Adding a highlight ✨

To highlight your print statement, add the letter h to the end of the function name

```bash
print_rh("Hello", label="My Label")
```

This will print the text with a background color, like this:

```bash
------------------------------------
[My Label]   : Hello
------------------------------------
```

## Example

Here is an example of how to use clPrint in your script:

```bash
import clprint

print_g("Hello, world!", label="Greeting")
print_b("This is a message in blue.", label="Info")
print_y("Warning: something went wrong.", label="Warning")
print_rh("This text is highlighted in red.", label="Error")
```

## Note

> clprint uses ANSI escape codes to change the color of the text in the terminal. This means that the colors may not show up correctly in IDEs or other environments that do not support ANSI escape codes.