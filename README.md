# C++

### index 
- [basics](#basics)
- [header](#header)
- [Data handling](#Data-handling)
- [flow of control](#flow-of-control)
- [string manipulation](#string-manipulation)
- [basic maths codes](https://github.com/Saujanya-rajvanshi/basic-maths)

### basics
- [character set](#character-set)
- [tokens](#tokens)
- [keywords](#keywords)
- [identifier](#identifier)
- [literals](#literals)
- [operator](#operator)
- [panctuator](#panctuator)
- [Barebones of c++ Program](#barebones-of-cpp-program)
- [data handling](#data-handling)
- [boiler plate code](#boile-plate-code)
- [next line](#next-line)
- [output & input](#output-and-input)

##### character set
```cpp
C++ Character Set

🌸 Letters: A–Z, a–z

🌸 Digits: 0–9

🌸 Special symbols:** `+  -  *  /  %  =  <  >  !  &  |  ^  ~  ?  :  ;  ,  .  '  "  #  $  @  _  ( )  { }  [ ]

🌸 Whitespace characters:** space, tab (`\t`), newline (`\n`), carriage return (`\r`)

```
##### tokens
```cpp
Tokens in C++

🌸 Tokens are the **smallest units** of a C++ program.

🌸 Keywords:** `int`, `float`, `if`, `else`, `for`, `while`, `return`, etc.

🌸 Identifiers:** names of variables, functions, classes (e.g. `sum`, `main`, `count`)

🌸 Constants (literals):** fixed values like `10`, `3.14`, `'a'`, `"hello"`

🌸 Operators:** `+ - * / % = == < > && ||

🌸 Separators (punctuators):** `; , ( ) { } [ ]

```
##### keywords
```cpp
C++ Keywords

1. Basic & Data types
int, float, double, char, void, bool, short, long, signed, unsigned, wchar_t

2. Control statements
if, else, switch, case, default
for, while, do, break, continue, goto, return

3. Storage classes
auto, register, static, extern, mutable

4. Type modifiers & casting
const, volatile, typedef, using, sizeof, typeid

5. OOP related
class, struct, union, public, private, protected
this, new, delete, virtual, override, final, friend

6. Inheritance & polymorphism
inherit, (no direct keyword)
virtual, dynamic_cast, static_cast, reinterpret_cast, const_cast

7. Templates & namespaces
template, typename, namespace, export

8. Exception handling
try, catch, throw, noexcept

9. Others / advanced
inline, explicit, constexpr, decltype, operator
nullptr, true, false, asm

📌 Important note
 * Keywords cannot be used as identifiers
 * Total keywords ≈ 95 (C++20)

Interview one-liner
“Keywords are reserved words in C++ with predefined meaning and cannot be used as variable or function names.”
```
##### identifier
---
Identifier in C++

An **identifier** is the **name given to a variable, function, class, or object** in a C++ program.

🌸 Rules for identifiers

* Must start with a letter (A–Z / a–z) or **underscore (_)
* Can contain **letters, digits, and underscores
* Cannot start with a digit
* Cannot be a keyword
* Case-sensitive

🌸 Examples

✔ Valid: `sum`, `total_marks`, `_count`, `main`
❌ Invalid: `1num`, `float`, `total-marks`

👉 Identifiers are used to **identify program elements uniquely**.

---

##### literals
---
## Literals

Literals are fixed constant values used directly in a program.
Types of literals

🌸 Integer literals: 10, -5, 0, 100  - [integer](#integer)

🌸 Floating-point literals: 3.14, 0.5, 2.0 - [Floating-point](#Floating-point)

🌸 Character literals: 'a', 'Z', '9' -[Character](#Characters)

🌸 String literals: "Hello", "C++" -[string](#string)

🌸 Boolean literals: true, false -[boolean](#boolean)

🌸 Null pointer literal: nullptr -[null pointer](#null)

👉 Literals represent constant values that do not change during program execution.

---

###### integer 
---
## integers 

Integer Literals in C++ (Sub-types)

🌸 Decimal: base 10 → digits 0–9
    Examples: 10, 25, 100

🌸 Octal: base 8 → starts with 0
    Digits: 0–7
    Examples: 012, 075

🌸 Hexadecimal: base 16 → starts with 0x or 0X
    Digits: 0–9, A–F
    Examples: 0x1A, 0XFF

🌸 Binary (C++14 onwards): base 2 → starts with 0b or 0B
    Digits: 0 and 1
    Examples: 0b1010, 0B1101

conversion/
1. decimal to binary(2)/octal(8)/hexadecimal(16)
      A.B  devide A -|-- by 2/8/16   B  multiply 0.---*2/8/16

2. binary(2)/octal(8)/hexadecimal(16) to decimal
     A * (2/8/16) power n 

---

##### Floating-point
---
## floating point numbers literals
### 🔸 Definition

Floating-point numbers are numbers that **contain a decimal point** or are written in **exponential form**.

### 🔸 Types in C++

* `float` → single precision
* `double` → double precision (more accurate)
* `long double` → extended precision

### 🔸 Examples

* `3.14`
* `-0.5`
* `2.5e3` (means 2.5 × 10³)

### 🔸 Storage

Floating-point numbers are stored in **IEEE 754 format** using:

* Sign
* Exponent
* Mantissa (fraction)

### 🔸 Precision

* `float` → ~6–7 decimal digits
* `double` → ~15–16 decimal digits

### 🔸 Important Points

* Floating-point values are **approximate**, not exact
* Direct comparison (`==`) is unsafe
* Use a small **epsilon** for comparison

### 🔸 Common Issues

* Rounding errors
* Precision loss
* Overflow / underflow

### 🔸 Use Cases

* Scientific calculations
* Measurements
* Financial calculations (prefer `double`)
---

##### characters
---

## 💎 Character Literals

* **💠 Character**: stores a single symbol
* **💠 Type**: `char`
* **💠 Size**: 1 byte
* **💠 Written in**: single quotes `'A'`

### ✨ Includes

* 🔹 **Letters** → `A–Z`, `a–z`
* 🔹 **Digits** → `0–9`
* 🔹 **Special symbols** → `@ # $ %`
* 🔹 **Whitespace** → space, tab, newline

### ⚡ ASCII-based Storage

* `'A'` = 65, `'a'` = 97, `'0'` = 48

### 🛠 Escape Characters

* `\n` → newline
* `\t` → tab
* `\\` → backslash
* `\'` → single quote

### 📝 Common Functions

* `isalpha()` → check letter
* `isdigit()` → check digit
* `toupper()` → convert to uppercase
* `tolower()` → convert to lowercase

---

##### string
---

## 💎 String 

* **💠 String**: collection of characters
* **💠 Type**: `string` (STL)
* **💠 Header**: `<string>`

### ✨ Features

* 🔹 Dynamic size
* 🔹 Stores text data
* 🔹 Uses contiguous memory

### 🛠 Common Operations

* 🔹 **Length** → `length()` / `size()`
* 🔹 **Access** → `at(i)` / `[]`
* 🔹 **Add** → `append()` / `+`
* 🔹 **Remove** → `erase()`
* 🔹 **Clear** → `clear()`

### 📝 Input / Output

* 🔹 `cin` → single word
* 🔹 `getline()` → full line

### ⚡ Important Points

* 🔹 Indexing starts from 0
* 🔹 Strings are mutable
* 🔹 Safer than C-style strings

---

#####  boolean
---

## 💎 Boolean

* **💠 Boolean**: stores truth values
* **💠 Type**: `bool`
* **💠 Size**: usually 1 byte
* **💠 Values**: `true` / `false`

### ✨ Usage

* 🔹 Used in **conditions**, **flags**, and **logical operations**

### 🛠 Common Operators

* 🔹 `!` → NOT
* 🔹 `&&` → AND
* 🔹 `||` → OR

### 📝 Example

```cpp
bool isOn = true;
if(!isOn) {
    // executes if isOn is false
}
```

### ⚡ Important Points

* 🔹 Only two values: `true` or `false`
* 🔹 Can be used in arithmetic: `true = 1`, `false = 0`

---

##### null
---

## 💎 Null Pointer

* **💠 Null Pointer**: a pointer that points to nothing
* **💠 Type**: any pointer type (e.g., `int*`, `char*`)
* **💠 Value**: `nullptr` (C++11 and later)

### ✨ Usage

* 🔹 Indicates that the pointer **does not point to any valid memory**
* 🔹 Helps **avoid dangling pointers**

### 🛠 Example

```cpp
int* ptr = nullptr;  // pointer points to nothing
if(ptr == nullptr) {
    // safe check before using ptr
}
```

### ⚡ Important Points

* 🔹 `NULL` is older, `nullptr` is preferred in modern C++
* 🔹 Always initialize pointers to `nullptr` if not assigned
* 🔹 Dereferencing a null pointer → **runtime error**

---

##### operator
---

## 💎 C++ Operators

### ✨ Categories

* **💠 Arithmetic** → `+`, `-`, `*`, `/`, `%`
* **💠 Relational** → `==`, `!=`, `<`, `>`, `<=`, `>=`
* **💠 Logical** → `&&`, `||`, `!`
* **💠 Bitwise** → `&`, `|`, `^`, `~`, `<<`, `>>`
* **💠 Assignment** → `=`, `+=`, `-=`, `*=`, `/=`, `%=` …
* **💠 Increment / Decrement** → `++`, `--`
* **💠 Conditional / Ternary** → `?:`
* **💠 Comma** → `,`
* **💠 Pointer / Reference** → `*`, `&`, `->`
* **💠 Member / Scope** → `.`, `::`

---

### 🏆 Operator Precedence & Associativity

| **Precedence** | **Operator**                                                                 | **Description**                  | **Associativity** |            |              |
| -------------- | ---------------------------------------------------------------------------- | -------------------------------- | ----------------- | ---------- | ------------ |
| 1              | `::`                                                                         | Scope resolution                 | Left → Right      |            |              |
| 2              | `++`, `--`, `+`(unary), `-`(unary), `!`, `~`, `*`(dereference), `&`(address) | Unary operators                  | Right → Left      |            |              |
| 3              | `*`, `/`, `%`                                                                | Multiplication, division, modulo | Left → Right      |            |              |
| 4              | `+`, `-`                                                                     | Addition, subtraction            | Left → Right      |            |              |
| 5              | `<<`, `>>`                                                                   | Bitwise shift                    | Left → Right      |            |              |
| 6              | `<`, `<=`, `>`, `>=`                                                         | Relational                       | Left → Right      |            |              |
| 7              | `==`, `!=`                                                                   | Equality                         | Left → Right      |            |              |
| 8              | `&`                                                                          | Bitwise AND                      | Left → Right      |            |              |
| 9              | `^`                                                                          | Bitwise XOR                      | Left → Right      |            |              |
| 10             | `\|`                                                                         | Bitwise OR                       | Left → Right      |            |              |
| 11             | `&&`                                                                         | Logical AND                      | Left → Right      |            |              |
| 12             | `                                                                            |                                  | `                 | Logical OR | Left → Right |
| 13             | `?:`                                                                         | Ternary conditional              | Right → Left      |            |              |
| 14             | `=`, `+=`, `-=`, `*=`, `/=`, `%=` …                                          | Assignment                       | Right → Left      |            |              |
| 15             | `,`                                                                          | Comma                            | Left → Right      |            |              |

---

### ⚡ Notes

* 🔹 Higher precedence → evaluated first
* 🔹 Associativity → resolves **operators with same precedence**
* 🔹 Unary operators have **right-to-left** associativity
* 🔹 Always use parentheses `()` to avoid ambiguity

---

##### panctuator
---

## 💎 Punctuators (C++)

* **💠 Punctuators**: symbols used to **separate, group, or structure** code
* **💠 Role**: define **syntax and program flow**
* **💠 Do not perform operations** like operators

---

### ✨ Common Punctuators

| **Punctuator** | **Purpose**                       |
| -------------- | --------------------------------- |
| `;`            | Statement terminator              |
| `{ }`          | Block / scope                     |
| `( )`          | Function call, condition grouping |
| `[ ]`          | Array indexing                    |
| `,`            | Separator                         |
| `:`            | Labels, ternary, initializer list |
| `.`            | Member access                     |
| `->`           | Pointer member access             |
| `::`           | Scope resolution                  |
| `#`            | Preprocessor directive            |
| `...`          | Variadic arguments                |

---

### ⚡ Examples

* `;` → ends a statement
* `{ }` → defines scope of loops / functions
* `( )` → used in `if`, `while`, function calls
* `#include` → uses `#` punctuator

---

### 📝 Important Points

* 🔹 Punctuators **do not produce values**
* 🔹 Used to **organize and structure** code
* 🔹 Essential for **syntax correctness**
* 🔹 Different from operators, but some symbols overlap

---

###### barebones of cpp program
---

## 💎 Barebones of C++ Program

### 🔹 Program Structure

* Starts from `main()`
* Statements end with `;`

### 🔹 Expressions

* Produce a value
* Example: `a + b`, `x > 5`

### 🔹 Statements

* Perform actions
* Example: declaration, assignment, `if`, `cout`

### 🔹 Comments

* `//` → single-line
* `/* */` → multi-line

### 🔹 Blocks

* Defined using `{ }`
* Same braces = same scope

---

###### header

### **#include <bits/stdc++.h>**
#include <bits/stdc++.h> is a non-standard header that includes almost all standard C++ libraries at once.

* It is mainly used in competitive programming.
* It pulls in headers like:
<iostream>, <vector>, <algorithm>, <map>, <set>, <stack>, <queue>, <cmath>
So you don’t need to include each one separately.


## ❌ Libraries it does **NOT** include

1. **Non-standard / compiler-specific headers**

These are outside the C++ standard:

* `<windows.h>`
* `<conio.h>`
* `<unistd.h>`
* `<dos.h>`

Reason: They are **OS/compiler specific**, not C++ STL.

---

2. **C headers without `c` prefix (sometimes)**

It includes:

* `<cstdio>`, `<cstring>`, `<cmath>`

But **not guaranteed** to include:

* `<stdio.h>`
* `<string.h>`
* `<math.h>`

(Use the `c` versions in C++)

---

 3. **Graphics / GUI libraries**

* `<graphics.h>`
* `<SFML/*>`
* `<GL/gl.h>`
* `<SDL.h>`

These are **external libraries**, not STL.

---

4. **Threading / system-level libraries (sometimes missing)**

May not reliably include:

* `<thread>`
* `<mutex>`
* `<condition_variable>`
* `<atomic>`

(Some GCC versions include them, some don’t → **not safe to rely on**)

---

5. **Networking / modern C++ libs**

* `<asio>`
* `<boost/*>` (Boost is external)

---

###### Data handling
---

# 💎 Data Handling in C++

* **Data Handling**
* **Data handling** refers to **storing, processing, and manipulating data** in a program.
* C++ handles data using **data types, variables, constants, and operators**.

---

###  Data Types in C++
* **Data Type** specifies:
  * Type of data
  * Size in memory
  * Range of values
  * Operations allowed

---

## 🏗 Classification of Data Types in C++

 1. Built-in (Core / Primitive)
 2. Derived
 3. User-defined

---

### 💎 Core (Built-in) Data Types

 Characteristics

* Predefined in C++
* Fast and memory-efficient
* Store **single values**

---

## 🔰 Core Data Types – Flow Chart (Hierarchy)

```
                Core Data Types
                       |
        --------------------------------------------------------------------
        |              |               |              |                     |
     Numeric         sets            none          sequence              mapping
        |                                             |                     |
   --------------------------                         ----- string        dictionary
   |            |           |                         |
 Integer     Floating      complex                    -----tuple
                                                      |
                                                      -----list
```

---

## 💎 Numeric Data Types

### 🔹 Integer Types

* Used to store **whole numbers**
* No decimal point

| Type            | Description          |
| --------------- | -------------------- |
| `int`           | Standard integer     |
| `short int`     | Smaller range        |
| `long int`      | Larger range         |
| `long long int` | Very large numbers   |
| `unsigned int`  | Only positive values |

---

### 🔹 Floating-Point Types

* Used to store **decimal numbers**

| Type          | Precision          |
| ------------- | ------------------ |
| `float`       | Single precision   |
| `double`      | Double precision   |
| `long double` | Extended precision |

---

## 💎 Character Data Type

### 🔹 `char`

* Stores **single character**
* Written in **single quotes**
* Size: **1 byte**
* Stored using **ASCII values**

Examples:

* `'A'`, `'9'`, `'@'`

---

## 💎 Boolean Data Type

### 🔹 `bool`

* Stores **true / false**
* Used in **conditions and decisions**
* Internally:

  * `true` → 1
  * `false` → 0

---

## 💎 Void Data Type

### 🔹 `void`

* Represents **no value**
* Used when:

  * Function returns nothing
  * Generic pointers

---

## 💎 Mutable vs Immutable Data (C++ Perspective)

> C++ does **not strictly enforce** mutability like Python, but conceptually:

---

### 🔹 Mutable Data

* Data that **can be changed**
* Examples:

  * Variables
  * Arrays
  * Objects
  * `string` (STL)

✔ Value can be modified after creation

---

### 🔹 Immutable Data

* Data that **cannot be changed once created**
* Achieved using:

  * `const` keyword
  * Literal values

✔ Prevents accidental modification

---

## 💎 Derived Data Types

* Formed using **core data types**

| Type      | Description             |
| --------- | ----------------------- |
| Array     | Collection of same type |
| Pointer   | Stores address          |
| Reference | Alias of variable       |
| Function  | Block of code           |

---

## 💎 User-Defined Data Types

* Created by programmer

| Type                | Purpose               |
| ------------------- | --------------------- |
| `struct`            | Group different types |
| `union`             | Shared memory         |
| `enum`              | Named constants       |
| `typedef` / `using` | Alias for data type   |
| `class`             | Blueprint for objects |

---

## ⚡ Key Exam Points

* Core data types store **single values**
* Integer → whole numbers
* Floating → decimal values
* `char` → single character
* `bool` → true / false
* `void` → no value
* `const` helps achieve immutability
* Flow-chart classification is **very important for theory exams**

---

##### flow of control
---
# Flow of Control in C++ – Complete Notes

Flow of control refers to the **order in which statements in a C++ program are executed**. By default, execution is **sequential (top to bottom)**, but flow-control statements allow us to change this order based on **conditions, loops, or jumps**.

---

## 1. Types of Flow of Control in C++

C++ flow of control is broadly classified into:

1. **Sequential Statements**
2. **Decision Making / Conditional Statements**
3. **Looping / Iteration Statements**
4. **Jump Statements**

---

## 2. Sequential Control

* Statements execute **one after another** in the order written.
* No condition or repetition involved.

Example:

```cpp
int a = 10;
int b = 20;
int c = a + b;
```

---

## 3. Decision Making Statements

Used to **execute statements based on conditions**.

### 3.1 if Statement

* Executes a block **only if condition is true**.

Syntax:

```cpp
if (condition) {
    // statements
}
```

Example:

```cpp
if (a > b) {
    cout << "A is greater";
}
```

---

### 3.2 if–else Statement

* Executes one block if condition is true, otherwise another.

Syntax:

```cpp
if (condition) {
    // true block
} else {
    // false block
}
```

---

### 3.3 if–else if–else Ladder

* Used when **multiple conditions** are to be checked.

Syntax:

```cpp
if (condition1) {
}
else if (condition2) {
}
else {
}
```

---

### 3.4 Nested if

* An if statement inside another if.

Example:

```cpp
if (a > b) {
    if (a > c) {
        cout << "A is largest";
    }
}
```

---

### 3.5 switch Statement

* Used to select one block from **multiple choices**.
* Works with **int, char, enum** (not float or string).

Syntax:

```cpp
switch(expression) {
    case value1:
        // code
        break;
    case value2:
        // code
        break;
    default:
        // code
}
```

Important Points:

* `break` prevents **fall-through**
* `default` is optional

---

## 4. Looping Statements

Used to **repeat a block of code** multiple times.

### Types of Loops:

1. while loop
2. do–while loop
3. for loop

---

### 4.1 while Loop (Entry Controlled)

* Condition is checked **before** loop body execution.

Syntax:

```cpp
while (condition) {
    // loop body
}
```

Example:

```cpp
int i = 1;
while (i <= 5) {
    cout << i;
    i++;
}
```

---

### 4.2 do–while Loop (Exit Controlled)

* Loop body executes **at least once**.

Syntax:

```cpp
do {
    // loop body
} while (condition);
```

---

### 4.3 for Loop

* Best suited when number of iterations is known.

Syntax:

```cpp
for (initialization; condition; increment) {
    // loop body
}
```

Example:

```cpp
for (int i = 1; i <= 5; i++) {
    cout << i;
}
```

---

## 5. Nested Loops

* One loop inside another.
* Commonly used for **2D arrays and patterns**.

Example:

```cpp
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 3; j++) {
        cout << "*";
    }
}
```

---

## 6. Jump Statements

Used to **transfer control abruptly**.

### 6.1 break

* Terminates loop or switch immediately.

```cpp
break;
```

---

### 6.2 continue

* Skips current iteration and moves to next.

```cpp
continue;
```

---

### 6.3 goto (Not Recommended)

* Transfers control to a labeled statement.

Syntax:

```cpp
goto label;
...
label:
```

Reason to avoid:

* Makes code **hard to read and debug**

---

### 6.4 return

* Exits from a function and returns value.

```cpp
return 0;
```

---

## 7. Conditional Operator (Ternary Operator)

* Short form of if–else.

Syntax:

```cpp
(condition) ? expr1 : expr2;
```

Example:

```cpp
int max = (a > b) ? a : b;
```

---

## 8. Infinite Loops

A loop that **never terminates**.

Example:

```cpp
while (true) {
}
```

---

## 9. Common Mistakes

* Missing `break` in switch
* Infinite loops due to wrong condition
* Using `=` instead of `==` in conditions

---

## 10. Exam-Oriented Summary

* Flow of control defines execution order
* Decision statements → if, else, switch
* Looping → for, while, do–while
* Jump → break, continue, goto, return

---

### One-line Definition:

> Flow of control statements control the execution order of a program based on conditions, loops, and jumps.


##### string manipulation
---

# 📘 C++ String Manipulation – Complete Notes

---

## 🔹 What is a String?

A **string** is a sequence of characters used to store text.

In C++, strings can be handled in **two ways**:

1. **C-style strings (character arrays)**
2. **C++ `string` class (STL)**

---

## 🔹 Types of Strings in C++

### 1️⃣ C-style Strings

* Implemented using **character arrays**
* End with a **null character `\0`**

```cpp
char str[20] = "Hello";
```

📌 Stored as: `H e l l o \0`

---

### 2️⃣ C++ String Class (`<string>`)

* Part of **Standard Template Library (STL)**
* Dynamic, safer, and easier to use

```cpp
#include <string>
string s = "Hello";
```

---

## 🔹 Input & Output of Strings

### Using `cin` and `cout`

```cpp
string s;
cin >> s;      // reads single word
cout << s;
```

### Using `getline()` (recommended)

```cpp
string s;
getline(cin, s);   // reads full line with spaces
```

---

## 🔹 Common String Functions (STL)

| Function              | Description               |
| --------------------- | ------------------------- |
| `length()` / `size()` | Returns length of string  |
| `empty()`             | Checks if string is empty |
| `clear()`             | Clears string             |
| `append()`            | Adds string at end        |
| `insert()`            | Inserts string            |
| `erase()`             | Removes part of string    |
| `replace()`           | Replaces substring        |
| `find()`              | Finds substring           |
| `substr()`            | Extracts substring        |
| `compare()`           | Compares strings          |

---

## 🔹 String Length

```cpp
string s = "Hello";
cout << s.length();   // 5
```

---

## 🔹 Concatenation (Joining Strings)

### Using `+` operator

```cpp
string a = "Hello";
string b = "World";
string c = a + " " + b;
```

### Using `append()`

```cpp
a.append(b);
```

---

## 🔹 Accessing Characters

```cpp
string s = "Hello";
cout << s[0];      // H
cout << s.at(1);   // e
```

---

## 🔹 Comparing Strings

### Using `==`

```cpp
if(a == b)
```

### Using `compare()`

```cpp
s1.compare(s2);
```

| Return Value | Meaning |
| ------------ | ------- |
| `0`          | equal   |
| `<0`         | s1 < s2 |
| `>0`         | s1 > s2 |

---

## 🔹 Substring

```cpp
string s = "Programming";
string sub = s.substr(0, 7); // Program
```

---

## 🔹 Finding a Substring

```cpp
string s = "Hello World";
cout << s.find("World"); // returns index
```

📌 If not found → returns `string::npos`

---

## 🔹 Insert & Erase

### Insert

```cpp
s.insert(5, " C++");
```

### Erase

```cpp
s.erase(5, 3);
```

---

## 🔹 Replace

```cpp
s.replace(0, 5, "Hi");
```

---

## 🔹 C-Style String Functions (`<cstring>`)

| Function   | Purpose     |
| ---------- | ----------- |
| `strlen()` | Length      |
| `strcpy()` | Copy        |
| `strcat()` | Concatenate |
| `strcmp()` | Compare     |

Example:

```cpp
char a[10] = "Hi";
char b[10] = "Hello";
strcpy(a, b);
```

---

## 🔹 Conversion Between String Types

### string → char array

```cpp
string s = "Hello";
char ch[10];
strcpy(ch, s.c_str());
```

---

## 🔹 Traversing a String

### Using loop

```cpp
for(int i = 0; i < s.length(); i++)
    cout << s[i];
```

### Using range-based loop

```cpp
for(char c : s)
    cout << c;
```

---

## 🔹 Common String Programs (Important)

✔ Reverse a string
✔ Check palindrome
✔ Count vowels/consonants
✔ Convert to uppercase/lowercase
✔ Compare two strings
✔ Find frequency of characters

---

## 🔹 Advantages of C++ `string` over C-style strings

| C-style          | C++ string       |
| ---------------- | ---------------- |
| Fixed size       | Dynamic size     |
| Error-prone      | Safe             |
| Manual functions | Built-in methods |

---

## 🔹 Exam & Viva Points ⭐

* `getline()` is used for strings with spaces
* `string::npos` means not found
* `string` is part of STL
* Prefer `string` over `char[]`

---

## ✅ Conclusion

C++ string manipulation is **easy, powerful, and safe** using the STL `string` class and is **highly preferred** over traditional C-style strings.

---

📌 **Tip for Exams**: Always write examples + function names for full marks.
