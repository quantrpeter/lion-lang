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

## Example Syntax

```
PRINT "Hello, world!"
REPEAT 4
  FORWARD 100
  RIGHT 90
END
SET COLOR "red"
CIRCLE 50
```

## Core Features

1. **Commands**: PRINT, FORWARD, BACK, LEFT, RIGHT, CIRCLE, SET COLOR, REPEAT, END
2. **No variables at first** (optional later)
3. **No functions or procedures** (optional later)
4. **REPEAT** for loops, no conditionals at first
5. **All numbers are integers**
6. **All strings in double quotes**
7. **Immediate drawing (turtle graphics) and text output**

## Example Program

```
PRINT "Let's draw a square!"
REPEAT 4
  FORWARD 100
  RIGHT 90
END
```

## Visual Feedback

- Turtle graphics window for drawing commands
- Console for PRINT output

---

Want to help? Try writing a simple interpreter or suggest new commands!

