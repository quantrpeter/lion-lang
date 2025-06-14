# Lion Lang

A new programming language for kids, inspired by BASIC and Logo. Designed for simplicity, fun, and learning.

![](https://github.com/quantrpeter/lion-lang/blob/main/doc/image/Lion%20Lang%20Banner.png?raw=true)

# Language Specification

## Goals
- Extremely simple syntax (one command per line)
- English-like keywords
- Immediate visual or text output
- Minimal setup, runs in a REPL or simple interpreter
- Safe: no complex types, no pointers, no advanced concepts

## Types
- **Integer**: Whole numbers (e.g., 10, -5)
- **Float**: Decimal numbers (e.g., 3.14, -2.5)
- **String**: Text in double quotes (e.g., "hello")

## Example Syntax

```
LET x = 10
LET y = 3.14
LET name = "Cub"
PRINT name
PRINT x + y
```

## Functions
- Define with `DEF` and end with `END`
- Use `RETURN` to return a value

```
DEF SQUARE(n)
  RETURN n * n
END
PRINT SQUARE(5)
```

## Built-in Functions

- **PRINT(value)**: Output text or numbers to the console
- **LEN(string)**: Returns the length of a string
- **RANDOM(min, max)**: Returns a random integer between min and max
- **TO_INT(value)**: Converts a value to integer
- **TO_FLOAT(value)**: Converts a value to float
- **TO_STRING(value)**: Converts a value to string
- **SQRT(value)**: Returns the square root of a number
- **ABS(value)**: Returns the absolute value
- **ROUND(value)**: Rounds a float to the nearest integer

Example usage:
```
LET n = LEN("hello")
PRINT RANDOM(1, 10)
PRINT TO_STRING(123)
PRINT SQRT(16)
```

## Core Features

1. **Commands**: PRINT, FORWARD, BACK, LEFT, RIGHT, CIRCLE, SET COLOR, REPEAT, END, LET, DEF, RETURN
2. **Variables**: Only integer, float, and string types
3. **Functions**: Simple function definition and call
4. **Built-in functions**: See above
5. **REPEAT** for loops, no conditionals at first
6. **All numbers are integer or float**
7. **All strings in double quotes**
8. **Immediate drawing (turtle graphics) and text output**

## Example Program

```
LET side = 100
DEF draw_square(size)
  REPEAT 4
    FORWARD size
    RIGHT 90
  END
END
PRINT "Let's draw a square!"
draw_square(side)
```

## Visual Feedback

- Turtle graphics window for drawing commands
- Console for PRINT output

---

Want to help? Try writing a simple interpreter or suggest new commands!

