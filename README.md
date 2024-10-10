# Project 00 For NeXT CS
### Class Period:
### Name0: YOUR NAME HERE
### Name1: OTHER NAME HERE (delete this line if you are working solo)
---

### Description (see bottom for skill list)
Your goal is to write a functional analog clock program, (see class website for an example image). Your code should contain the following (but can, and should, have other things).
* Global variables
* Functions
  * `setup`
  * `draw`
  * Other functions to help maintain your clock (some further guidelines below).

Important features you need to implement:
* On startup, the program should get the current time using processing's own `hour()`, `minute()`, `second()` functions.
  * After this point, all time updating should be handled by your program itself, __not__ by calling the processing timekeeping functions.
* Different colors for the background and clock face.
* Clock hands that move correctly, including the second hand.
* Clock hands that are different in appearance.

If you would like to improve upon this base version, here are some things you might consider adding:
* Marks for hours, minutes.
* Smooth movement of the timekeeping hands.
* Adding numbers to the display.
* Including the date in some way.
* Other cool visual features.

### Phase 0: Design
#### Due: Friday 10/11, 4pm
Fill in the following sections of this document with your initial design choices. Once finished, this section shoudl reflect your final project.
#### Global variables:
List all global variables you will be using here. Include type, name, and purpose.

#### Functions:
List all methods here, for `setup` and `draw`, explain what they will be doing. For all other methods, include the name, return type, and description.




### Skills
| Skill | Minimal Competency | Developing Competency | Competency | Mastery
| --- | --- | --- | --- | --- |
| 1. Basic Drawing Functions (line, circle, square, rect, ellipse) |  Can use one basic 2D drawing function. | Can use two basic drawing functions. | Can use all the basic drawing functions. | Can use multiple basic drawing functions to draw a complex shape. |
| 2. Controlling Color State |  Can set the fill or stroke color of a 2D shape. | Can set the fill and stroke color of a 2D shape. | Can set the fill and stroke color and the stroke weight of a 2D shape. | Can control the fill and stroke colors and the stroke weights of multiple 2D shapes. |
| 3. Using Colors |  Can set colors using separate Red, Green, and Blue values. | Can set colors using RGB values or hexcode values. | Can create and work with `color` variable types. | Can explain how the `color` data type represents color values. |
| 4. Primitive Variables and Types |  Can declare, initialize, and use `int` variables. | Can declare, initialize, and use `int` and `float` variables. | Can explain the differences and use the different integer and floating point variable types. | Can explain the differences between, use, and explain how the different primitive variables types represent data. |
| 5. Working with Boolean Values |  Understands the purpose of boolean values. | Demonstrates the appropriate use of comparison operators. | Demonstrates the appropriate use of comparison and boolean operators. | Writes functions that take in boolean values and/or return boolean values. |
| 6. Working with `setup` and `draw` |  Can write a valid `setup` function that sets initial conditions for a processing program. | Can write a valid `setup` function, and can write a valid `draw` function that generates different program output each frame. | Can create global variables that are initialized in `setup` and modified in `draw`. | Can use global variables, custom functions, and `setup` and `draw` to produce a full processing program. |
| 7. Controlling Program Speed |  Can set the frame rate for a processing program. | Can set the frame rate based on a specified speed. | Can control program output based on the current frame number. | Can start and stop the action of a processing program. |
| 8. Custom Functions |  Can identify the return type, name, parameter list, and body of a function. | Can write a function given a header and description. | Can write a function, including selecting appropriate return and parameter types. | Can write multiple functions and use variable scope accurately. |
| 9. Writing Readable Code |  Uses descriptive identifiers. | Uses indentation and newlines to create more readable code, and descriptive identifiers. | Uses inline and block comments when appropriate. Uses indentation and newlines, and descriptive identifiers. | Can take a large programming task and break it up into smaller functions. |
| 10. Debugging Practices |  Can use `println` statements to help debug code. | Consistently uses `println` statements while debugging. | Consistently uses `println` statements and commenting while debugging. | Creates visual output in the program window while debugging. |
| 11. Conditional Statements |  Can use a single `if` statement correctly. | Can use combined `if` and `else` statements correctly. | Can use `if`, `else if`, and `else` correctly multiples times in a program. | Can use multiple styles of combinations of conditional statements (i.e. nested, sequential) in a single program. |
| 12. Loops |  Can use a basic `while` loop. | Can use a basic `for` loop with a variable modified by an increment (`++`) or decrement (`--`) operator. | Can use `for` loops with a variable controlled by `--`, `++`, and other arithmetic operations as appropriate. | Can use both `for` and `while` loops when appropriate, and explain why one is a better choice over another in a given situation. |
