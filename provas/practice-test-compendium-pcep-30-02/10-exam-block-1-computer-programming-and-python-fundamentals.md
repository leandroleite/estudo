# QUESTAO NUMERO 1

A program which is used to transform a source file into an **executable** binary file is called:

- (A) an IDE.
- (B) a compiler.
- (C) a linker
- (D) an interpreter.

## Answer: B

## Explicação

**A compiler** (also known as a translator) is designed to **translate** a program written in a high-level programming language (like C++) into a binary code deployed inside an executable file.

- Compiler: A program that **translates** source code written in a high-level language (e.g., C++, Java) into **machine code or an executable binary file**.
- IDE: A software application that provides a complete environment for writing, editing, debugging, and managing code.
- Linker: A program that **combines multiple object files** (produced by the compiler) and libraries into a single executable file.
- Interpreter: A program that **executes code line by line** without converting it into a separate executable file.

# QUESTAO NUMERO 2

A process in which the source code is **immediately executed** without translating it into a machine code is called:

- (A) debugging.
- (B) interpretation.
- (C) linking.
- (D) compilation.

## Answer: B

## Explicação

**Interpretation** (in the IT/programming sense) is a process in which the source code is executed on-the-fly, and this process is not accompanied by the creation of the machine code.

- Interpretation: A process where source code is **executed directly, line by line**, without converting it into machine code beforehand.
- Compilation: Converts the **entire source code** into **machine code** (binary) before execution.
- Linking: Combines **compiled object files** and **libraries** into a single executable file.
- Debugging: The process of **finding and fixing errors (bugs)** in the source code.

# QUESTAO NUMERO 3

A code written in a **high-level** programming language is called:

- (A) the ASCII code.
- (B) a source code.
- (C) machine code.
- (D) a binary code.

## Answer: B

## Explicação

**A source code** is a code written (usually by humans) in a programming language. This code needs either a compiler or an interpreter to be run.

- Source Code: Human-readable instructions written in a **high-level programming language** (e.g., Python, Java, C++).
- Machine Code: Low-level instructions that the **CPU can execute directly**.
- Binary Code: Data represented in **binary digits (0s and 1s)**.
- ASCII Code:A character encoding standard that maps **text characters to numeric codes**.

# QUESTAO NUMERO 4

A **syntax** is a part of a language definition which describes the rules used to build:

- (A) the symbols from a set of dots.
- (B) the sentences from a set of words.
- (C) the words from a set of symbols.
- (D) the data from digits.

## Answer: B

## Explicação

A **syntax** is a set of rules which must be obeyed to build grammatically correct (not necessarily meaningful) sentences in any language.

- Syntax: Refers to the **set of rules that define** the structure of statements in a programming language.
- Semantics: Refers to the **meaning of the statements** in a programming language.

# QUESTAO NUMERO 5.1

Select literals correspond the data type **string**.

- (A) "False"
- (B) "\""
- (C) False
- (D) True

## Answer: AB

## Explicação

- "False" is a string, despite its somewhat confusing contents.
- "\"" is a string of length 1 – it contains one quotation mark only.
- True and False are two possible Boolean values.

String: A sequence of characters enclosed in quotes (" " or ' ').

- Can include letters, numbers, symbols, and even spaces.
- Length can be zero or more characters.
- Strings are immutable (cannot be changed after creation).

# QUESTAO NUMERO 5.2

Select literals correspond the data type **boolean**.

- (A) "False"
- (B) False
- (C) True

## Answer: BC

## Explicação

- "False" is a string, despite its somewhat confusing contents.
- True and False are two possible Boolean values.

Boolean: A data type with only two possible values: True or False

# QUESTAO NUMERO 5.3

Select literals correspond the data type **integer**.

- (A) 1.41421356237
- (B) 1_000_000
- (C) -1

## Answer: BC

## Explicação

- 1_000_000 is an integer value – underscores are here to make the number (one million in this case) easier to read.
- 1.41421356237 is a float – to be precise, it's an approximation of the square root of 2.0.
- -1 is an integer value equal to minus one.

Integer: Whole numbers (positive, negative, or zero) without a decimal point.

- Can include underscores for readability (e.g., 1_000_000).

# QUESTAO NUMERO 5.4

Select literals correspond the data type **float**.

- (A) 1.41421356237
- (B) -1
- (C) -.1

## Answer: AC

## Explicação

- 1.41421356237 is a float – to be precise, it's an approximation of the square root of 2.0.
- -1 is an integer value equal to minus one.
- -.1 is a float value equal to minus one tenth.

Float: Numbers with a decimal point or in scientific notation.

# QUESTAO NUMERO 7

What is the correct order of arithmetic operations, where the first position has the highest priority and the last position has the lowest priority?Arrange the arithmetic operations in the order which reflects their priorities, where the top-most position has the highest priority and the bottom-most position has the lowest priority.

- (A) EXPONENTIATION MULTIPLICATION ADDITION
- (B) EXPONENTIATION DIVISION SUBTRACTION
- (C) MULTIPLICATION EXPONENTIATION ADDITION
- (D) SUBTRACTION DIVISION EXPONENTIATION

## Answer: AB

## Explicação

Python's arrangement of these arithmetic operators is as follows:

- Parentheses ()
- Exponentiation \*\*
- Multiplication, Division, Floor Division, Modulus
- Addition and Subtraction

# QUESTAO NUMERO 8

Which of the following expressions evaluate to a non-zero result?

- (A) 4 / 2 + 2 ** 1
- (B) 4 / 2 - 2 ** 1
- (C) 1 // 2 + 3 * 4
- (D) 1 ** 2 - 4 // 3

## Answer: AC

## Explicação

- 1 // 2 + 3 * 4 evaluates to **12**.
- 4 / 2 + 2 ** 1 evaluates to **4.0** (note – it’s a float as a division operator always produces floats).

# QUESTAO NUMERO 9

Which of the following expressions evaluate to zero?

- (A) 1 // 3 * 3 ** 0
- (B) 1 - 2 // 3 + 4
- (C) 1 ** 2 / 2 // 3
- (D) 4 - 3 // 2 + 1

## Answer: AC

# QUESTAO NUMERO 10

Which of the following variable names are legal in Python?

- (A) i_am_a_variable
- (B) samplevariable
- (C) For
- (D) _fun
- (E) 2nd_class
- (F) @home
- (G) for

## Answer: ABCD

## Explicação

- samplevariable: Must start with a letter or underscore (_)
- _fun: Can start with an underscore
- i_am_a_variable: Can contain letters, digits, and underscores after the first character
- For, for: Case-sensitive
- 2nd_class: Cannot start with a digit
- @home: Cannot contain special characters other than underscore
- for: Cannot be a reserved keyword in Python
- Cannot contain spaces

# QUESTAO NUMERO 11

Which of the following variable names are legal in Python?

- (A) securityinspectorsuperintendentsecretagent007
- (B) true5
- (C) TRUE
- (D) True
- (E) &sleep;
- (F) maxValue
- (G) 365

## Answer: ABCF

## Explicação

- securityinspectorsuperintendentsecretagent007: correct (rather too long, but perfectly legal)
- Must start with a letter or underscore (_)
- i_am_a_variable: Can contain letters, digits, and underscores after the first character
- TRUE, True: Case-sensitive
- 365: Cannot start with a digit
- &sleep;: Cannot contain special characters other than underscore
- True: Cannot be a reserved keyword in Python

# QUESTAO NUMERO 12

What is the expected output of the following code?

~~~python
a = 5
# a = a + a
print(a)
~~~

- (A) 55
- (B) Error message
- (C) 5
- (D) 10

## Answer: C

## Explicação

- The a = a + a part of the code is commented, and the interpreter ignores this line.

The correct output is 5, because the comment prevents the addition from happening.

- Single-line comments start with #
- Multi-line comments can be created using triple quotes (''' or """)

# QUESTAO NUMERO 13

What is the expected output of the following code?

~~~Python
a = 1 # + 5
a = a + a
# a = a + 1
print(a) # Line 4
~~~

- (A) 12
- (B) Error message
- (C) 3
- (D) 2

## Answer: D

## Explicação

The interpreter ignores the code lines preceded by the # symbol.

- Single-line comments start with #
- Multi-line comments can be created using triple quotes (''' or """)

# QUESTAO NUMERO 14

Which of the following line of code asks the user for an integer value and assigns it to the floor variable?

- (A) floor = int(input("Enter floor number:"))
- (B) floor = input(int("Enter floor number:"))
- (C) floor = float(input("Enter floor number:"))
- (D) floor = input(float("Enter floor number:"))

## Answer: A

## Explicação

- **input(msg)**: Displays the prompt msg to the user. Waits for the user to type something and press Enter. Returns the typed text as a string.
- **int(...)**: Converts the returned string from input() into an integer.

If the user types something that isn’t a valid integer (e.g., "three" or "4.5"), Python raises a ValueError.

# QUESTAO NUMERO 15

Which of the following line of code asks the user to build a line of code which prints the values assigned to the width and height variables separated by a multiplication sign ("×").

- (A) print(width, height, sep="x")
- (B) print(width, height, end="x")
- (C) input(width, height, sep="x")
- (D) input(width, height, end="x")
- (E) print(width, height)
- (F) input(width, height)

## Answer: A

## Explicação

- print(...) outputs text to the console.
- sep="x": Separator placed between the items. Default is a space (" ")
- end="\n": What to append at the end of the line. Default is already "\n" (newline), so this line explicitly keeps the default behavior—after printing, it moves to the next line. If you set end="", it would not add a newline.

# QUESTAO NUMERO 16

Which of the following line of code asks the user for a string value and assigns it to the password variable?

- (A) password = int(input("Enter password:"))
- (B) password = input(int("Enter password:"))
- (C) password = input("Enter password:")

## Answer: C

## Explicação

- **input(msg)**: Displays the prompt msg to the user. Waits for the user to type something and press Enter. Returns the typed text as a string.

# QUESTAO NUMERO 17

Which of the following line of code asks the user for a float value and assigns it to the price variable?

- (A) price = int(input("Enter item price:"))
- (B) price = input(int("Enter item price:"))
- (C) price = float(input("Enter item price:"))
- (D) price = input(float("Enter item price:"))

## Answer: C

## Explicação

- **input(msg)**: Displays the prompt msg to the user. Waits for the user to type something and press Enter. Returns the typed text as a string.
- **int(...)**: Converts the returned string from input() into a float.
