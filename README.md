# C++

### index
- [History of C++](#History)
- [features of c++](#Features)
- [basics](#basics)
- [header](#header)
- [Data handling](#Data-handling)
- [flow of control](#flow-of-control)
- [function](#function)
- [Array](https://github.com/Saujanya-rajvanshi/Arrays-)
- [pointer](#pointer)
- [dynamic memory allocation](#dynamic-memory-allocation)
- [Structures & Unions](#Structures-Unions)
- [Object-Oriented Programming (OOP)](https://github.com/Saujanya-rajvanshi/THEORY?tab=readme-ov-file#Oops)
- [Exception Handling](#exception-handling)
- [File Handling](#file-handling)
- [Templates](#templates)
- [STL (Standard Template Library)](https://github.com/Saujanya-rajvanshi/STL)
- [Advanced C++ Concepts](#advanced-concept)
- [Competitive Programming / DSA Readiness](#Competitive-Programmings)
- [string manipulation](#string-manipulation)
- [basic maths codes](https://github.com/Saujanya-rajvanshi/basic-maths)



###### History
# 🎗 HISTORY

* The C++ language is an object-oriented programming language & is a combination of both low-level & high-level language - a Middle-Level Language.
* created, designed & developed by a Danish Computer Scientist - Bjarne Stroustrup at Bell Telephone Laboratories (now known as Nokia Bell Labs) in Murray Hill, New Jersey.
* **1979** – Bjarne Stroustrup at Bell Labs started working on a language called **“C with Classes”** to support object-oriented programming.
* **Early 1980s** – Features like **classes, constructors, destructors, and data hiding** were added to C.
* **1983** – The language was renamed **C++** (`++` means increment in C, indicating an improvement over C).
* **1985** – First commercial release of C++ and the book **“The C++ Programming Language”** by Bjarne Stroustrup was published.
* **1990** – C++ became widely popular for system and application development.

<img width="1042" height="745" alt="image" src="https://github.com/user-attachments/assets/f0df1c76-dd3c-400e-b11f-9ecee354efde" />


| **C++ Version**                | **Release Date** | **Major Changes / Features**                                                                                                 |
| ------------------------------ | ---------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **C++98** (ISO/IEC 14882:1998) | October 1998     | First official C++ standard, STL introduced, basic OOP features standardized                                                 |
| **C++03** (ISO/IEC 14882:2003) | February 2003    | Bug fixes to C++98, value initialization improvements                                                                        |
| **C++11**                      | August 2011      | Lambda expressions, `auto`, `nullptr`, uniform initialization, rvalue references, move semantics, `decltype`, smart pointers |
| **C++14**                      | August 2014      | Polymorphic lambdas, digit separators, variable templates, binary literals, `std::quoted`                                    |
| **C++17**                      | December 2017    | Fold expressions, `if`/`switch` with initializer, inline variables, `std::optional`, `std::variant`, `std::any`              |
| **C++20**                      | March 2020       | Concepts, ranges, coroutines, modules, reflection-like inspection of program entities, enhanced lambdas                      |
| **C++23**                      | Future Release   | Next major revision of C++ standard, further language and library enhancements                                               |


**C++ is a general-purpose, high-performance language** used in system software, game development, competitive programming, embedded systems, and large-scale applications.

###### Features
# 🎗 FEATURES

* **Object-Oriented Programming (OOP)**
  Supports classes, objects, inheritance, polymorphism, encapsulation, and abstraction.

* **Fast and Efficient**
  Close to hardware, suitable for system-level and high-performance applications.

* **Compiled Language**
  Programs are compiled, giving better performance and security.

* **Rich Standard Library (STL)**
  Provides containers, algorithms, iterators, and functions.

* **Supports Multiple Programming Styles**
  Procedural, object-oriented, and generic programming.

* **Memory Management**
  Uses pointers, dynamic memory allocation (`new`, `delete`).

* **Platform Independent**
  Same code can run on different platforms with little or no change.

* **Function Overloading**
  Allows multiple functions with the same name but different parameters.

* **Operator Overloading**
  Custom behavior for operators like `+`, `-`, `<<`, etc.

* **Exception Handling**
  Handles runtime errors using `try`, `catch`, and `throw`.

* **Templates**
  Supports generic programming for data types.

* **High Security**
  Data hiding using access specifiers (`private`, `protected`, `public`).


###### basics
# 🎗 BASICS 
- [character set](#character-set)
- [tokens](#tokens)
- [Barebones of c++ Program](#barebones-of-cpp-program)
- [Data Types (overview)](#Data-Types-overview)
- [Variables & Constants](#Variables-Constants)
- [Type Modifiers](#Type-Modifiers)
- [Type Conversion Type Casting](#Type-Conversion-Type-Casting)
- [sizeof operator](#sizeof-operator)
- [Comments](#Comments)
- [boiler plate code](#boile-plate-code)
- [next line](#next-line)
- [Escape Sequences](#Escape-Sequences)
- [output & input](#output-and-input)

###### character set
## 🧩 character set
* **Letters:** A–Z, a–z
* **Digits :** 0–9
* **Special symbols:** `+  -  *  /  %  =  <  >  !  &  |  ^  ~  ?  :  ;  ,  .  '  "  #  $  @  _  ( )  { }  [ ]
* **Whitespace characters:** space, tab (`\t`), newline (`\n`), carriage return (`\r`)

### Differences between whitespace characters

| Character           | Symbol | What it does                                   | Example / Use                   |
| ------------------- | ------ | ---------------------------------------------- | ------------------------------- |
| **Space**           | `' '`  | Adds a single blank gap                        | Separates words → `Hello World` |
| **Tab**             | `\t`   | Adds a horizontal gap (bigger than space)      | Indentation in code             |
| **Newline**         | `\n`   | Moves cursor to the **next line**              | End of a line                   |
| **Carriage Return** | `\r`   | Moves cursor to the **start of the same line** | Line overwrite                  |




###### tokens
## 🧩 tokens
 Tokens are the **smallest units** of a C++ program.
* **Keywords:** `int`, `float`, `if`, `else`, `for`, `while`, `return`, etc.
* - [tokens - keywords](#keywords)
* **Identifiers:** names of variables, functions, classes (e.g. `sum`, `main`, `count`)
* - [tokens - identifier](#identifier)
* **Constants (literals):** fixed values like `10`, `3.14`, `'a'`, `"hello"`
* - [tokens - literals](#literals)
* **Operators:** `+ - * / % = == < > && ||
* - [tokens - operator](#operators)
* **Separators (punctuators):** `; , ( ) { } [ ]
* - [tokens - panctuator](#panctuator)

###### keywords
## 🔮 keywords

* **Basic & Data types** :  int, float, double, char, string, void, bool, short, long, signed, unsigned, wchar_t
* **Control statements** : if, else, switch, case, default, for, while, do, break, continue, goto, return
* **Storage classes** : auto, register, static, extern, mutable
* **Type modifiers & casting** :  const, volatile, typedef, using, sizeof, typeid
* **OOP related** : class, struct, union, public, private, protected, this, new, delete, virtual, override, final, friend
* **Inheritance and polymorphism** : inherit, (no direct keyword), virtual, dynamic_cast, static_cast, reinterpret_cast, const_cast
* **Templates & namespaces** : template, typename, namespace, export
* **Exception handling** : try, catch, throw, noexcept
* **Others / advanced** : inline, explicit, constexpr, decltype, operator, nullptr, true, false, asm

###### Important note
 * Keywords cannot be used as identifiers
 * Total keywords ≈ 95 (C++20)


### Basic & Data types

int, float, double, char, string, void, bool, short, long, signed, unsigned, wchar_t

* switch , case , default
```cpp
int day = 5;

switch(day) {
    case 1:
        cout << "Monday";
        break;
    case 2:
        cout << "Tuesday";
        break;
    default:
        cout << "Invalid day";
}
```

### Control statements

if, else, switch, case, default, for, while, do, break, continue, goto, return

* goto
Used to jump to another part of program. <br>
Not recommended in modern programming.

```cpp
#include <iostream>
using namespace std;

int main() {
    int i = 1;

start:
    cout << i << endl;
    i++;

    if(i <= 3)
        goto start;

    return 0;
}
```

### Storage classes

* `auto` 

Automatically deduces type.

```cpp
auto x = 10;      // int
auto y = 3.14;    // double
auto name = "Hi"; // const char*
```

* `register` ⚠ (Deprecated/Removed)

Old keyword suggesting storing variable in CPU register.

```cpp
register int x = 5;
```

👉 Modern compilers ignore it.
❌ Removed in C++17.

---

* `static` 

#### a) Inside function → retains value

```cpp
void counter() {
    static int count = 0;
    count++;
    cout << count << endl;
}
```

Value persists between function calls.

#### b) Outside function → internal linkage

```cpp
static int x = 10;
```

Accessible only within that file.

* `extern` 

Used to declare a global variable from another file.

File1.cpp:

```cpp
int x = 100;
```

File2.cpp:

```cpp
extern int x;
```

Allows sharing global variable.

* `mutable` (Used in classes)

Allows modification inside `const` objects.

```cpp
class Test {
public:
    mutable int x;

    void change() const {
        x = 5;   // allowed because mutable
    }
};
```

Without `mutable`, this would give error.

### Type Modifiers & Casting

##### 1️. `const`

Value cannot change.

```cpp
const int x = 10;
```

##### 2️. `volatile`

Tells compiler: value may change unexpectedly (hardware, threads).

```cpp
volatile int flag;
```

##### 3️. `typedef`

Old way to create alias.

```cpp
typedef unsigned int uint;
uint x = 5;
```

##### 4️. `using`

Modern alias.

```cpp
using uint = unsigned int;
```

##### 5️. `sizeof`

Returns memory size (bytes).

```cpp
cout << sizeof(int);
```

##### 6️. `typeid`

Gets type information.

```cpp
#include <typeinfo>
cout << typeid(x).name();
```

### OOP Related

##### `class`

```cpp
class A {};
```

##### `struct`

Same as class, but default public.

```cpp
struct B {};
```

##### `union`

All members share same memory.

```cpp
union Data {
    int x;
    float y;
};
```

##### Access specifiers

```cpp
public:
private:
protected:
```

##### `this`

Pointer to current object.

```cpp
this->x = x;
```

##### `new` / `delete`

```cpp
int* p = new int(10);
delete p;
```

##### `virtual`

Enables runtime polymorphism.

```cpp
virtual void show();
```

##### `override`

```cpp
void show() override;
```

##### `final`

```cpp
class A final {};
```

##### `friend`

```cpp
friend void display();
```

### Inheritance & Casting

(No `inherit` keyword in C++)

```cpp
class B : public A {};
```

### Casting

##### `static_cast`

Compile-time safe cast.

```cpp
static_cast<double>(x);
```

##### `dynamic_cast`

Runtime casting (polymorphism).

```cpp
dynamic_cast<Derived*>(basePtr);
```

##### `reinterpret_cast`

Low-level cast.

```cpp
reinterpret_cast<long>(ptr);
```

##### `const_cast`

Removes const.

```cpp
const_cast<int&>(x);
```

### Templates & Namespace

##### `template`

```cpp
template <typename T>
T add(T a, T b) { return a+b; }
```

##### `typename`

Used in templates.

##### `namespace`

```cpp
namespace MySpace {
    int x = 5;
}
```

##### `export`

Rarely used (removed in modern standards for templates).


### Exception Handling

```cpp
try {
    throw 10;
}
catch(int x) {
    cout << x;
}
```

##### `noexcept`

```cpp
void func() noexcept {}
```

### Others / Advanced

##### `inline`

```cpp
inline int square(int x) { return x*x; }
```

##### `explicit`

```cpp
explicit A(int x);
```

Prevents implicit conversion.

##### `constexpr`

```cpp
constexpr int x = 5;
```

Compile-time constant.

##### `decltype`

```cpp
decltype(x) y = 10;
```

##### `operator`

```cpp
int operator+(A obj);
```

##### `nullptr`

```cpp
int* p = nullptr;
```

##### `true` / `false`

```cpp
bool flag = true;
```

##### `asm`

Inline assembly (rarely used).

```cpp
asm("nop");
```


###### identifier
## 🔮 identifier

An **identifier** is the **name given to a variable, function, class, or object** in a C++ program.

#### **Rules for identifiers**
* Must start with a letter (A–Z / a–z) or **underscore (_)
* Can contain **letters, digits, and underscores
* Cannot start with a digit
* Cannot be a keyword
* Case-sensitive

---
###### literals
## 🔮 literals

Literals are fixed constant values used directly in a program.

#### **Types of literals**
* **Integer literals :** 10, -5, 0, 100  - [integer](#integer-literals)
* **Floating-point literals :** 3.14, 0.5, 2.0 - [Floating-point](#Floating-point-literals)
* **Character literals :** 'a', 'Z', '9' -[Character](#Characters-literals)
* **String literals :** "Hello", "C++" -[string](#string-literals)
* **Boolean literals :** true, false -[boolean](#boolean-literals)
* **Null pointer literal :** nullptr -[null pointer](#null-literals)


## integer literals

Integer Literals in C++ (Sub-types)

#### **Decimal :** base 10 → digits 0–9
Examples: 10, 25, 100

#### **Octal :** base 8 → starts with 0
Digits: 0–7 <br>
Examples: 012, 075

#### **Hexadecimal :** base 16 → starts with 0x or 0X
* Digits: 0–9, A–F
* Examples: 0x1A, 0XFF

#### **Binary (C++14 onwards) :** base 2 → starts with 0b or 0B
* Digits: 0 and 1
* Examples: 0b1010, 0B1101

#### **conversion**
```
1. decimal to binary(2)/octal(8)/hexadecimal(16)
      A.B  devide A -|-- by 2/8/16   B  multiply 0.---*2/8/16

2. binary(2)/octal(8)/hexadecimal(16) to decimal
     A * (2/8/16) power n 
```


## Floating point literals
Floating-point numbers are numbers that **contain a decimal point** or are written in **exponential form**.

#### **Types in C++**
* `float` → single precision
* `double` → double precision (more accurate)
* `long double` → extended precision

* **Examples** -> `3.14` , `-0.5` , `2.5e3` (means 2.5 × 10³)

#### **Storage**
Floating-point numbers are stored in **IEEE 754 format** using:
* Sign
* Exponent
* Mantissa (fraction)

#### **Precision**
* `float` → ~6–7 decimal digits
* `double` → ~15–16 decimal digits

#### **Important Points**
* Floating-point values are **approximate**, not exact
* Direct comparison (`==`) is unsafe
* Use a small **epsilon** for comparison

#### **Common Issues**
* Rounding errors
* Precision loss
* Overflow / underflow



### IEEE-754 FORMAT

| Type       | Total Bits | Sign | Exponent | Mantissa | Bias     |
| ---------- | ---------- | ---- | -------- | -------- | -------- |
| **Single** | 32         | 1    | 8        | 23       | **127**  |
| **Double** | 64         | 1    | 11       | 52       | **1023** |


#### STEPS (Same for both)

* **Step 1: Convert number to binary**

Split → integer + fraction
Example: **13.25 → 1101.01**

* **Step 2: Normalize**

```
1101.01 = 1.10101 × 2³
```

* **Step 3: Sign bit**

* +ve → **0**
* −ve → **1**

* **Step 4: Exponent**

```
Exponent = Power + Bias
```

* Single: `3 + 127 = 130 → 10000010`
* Double: `3 + 1023 = 1026 → 10000000010`

* **Step 5: Mantissa**

Take bits **after leading 1**

```
10101 + zeros
```

* Single → 23 bits
* Double → 52 bits


* **FINAL FORMAT**
* **Single Precision (32-bit)**

```
Sign | Exponent(8) | Mantissa(23)
0 | 10000010 | 10101000000000000000000
```

* **Double Precision (64-bit)**

```
Sign | Exponent(11) | Mantissa(52)
0 | 10000000010 | 1010100000000000000000000000000000000000000000000000
```


## characters literals

* **Character**: stores a single symbol
* **Type**: `char`
* **Size**: 1 byte
* **Written in**: single quotes `'A'`

#### **Includes**
* **Letters** → `A–Z`, `a–z`
* **Digits** → `0–9`
* **Special symbols** → `@ # $ %`
* **Whitespace** → space, tab, newline

#### **ASCII-based Storage**
* `'A'` = 65, `'a'` = 97, `'0'` = 48

#### **Escape Characters**
* `\n` → newline
* `\t` → tab
* `\\` → backslash
* `\'` → single quote

#### **Common Functions**
* `isalpha()` → check letter
* `isdigit()` → check digit
* `toupper()` → convert to uppercase
* `tolower()` → convert to lowercase


## string literals

* **String**: collection of characters
* **Type**: `string` (STL)
* **Header**: `<string>`

#### **Features**
* Dynamic size
* Stores text data
* Uses contiguous memory

#### **Common Operations**
* **Length** → `length()` / `size()`
* **Access** → `at(i)` / `[]`
* **Add** → `append()` / `+`
* **Remove** → `erase()`
* **Clear** → `clear()`

#### **Input / Output**
* `cin` → single word
* `getline()` → full line

#### **Important Points**
* Indexing starts from 0
* Strings are mutable
* Safer than C-style strings


##  boolean literals

* **Boolean**: stores truth values
* **Type**: `bool`
* **Size**: usually 1 byte
* **Values**: `true` / `false`

#### **Usage**
*  Used in **conditions**, **flags**, and **logical operations**

#### **Common Operators**
*  `!` → NOT
*  `&&` → AND
*  `||` → OR

* **Example**

```cpp
bool isOn = true;
if(!isOn) {
    // executes if isOn is false
}
```

#### **Important Points**
* Only two values: `true` or `false`
* Can be used in arithmetic: `true = 1`, `false = 0`


##### null literals

* **Null Pointer**: a pointer that points to nothing
* **Type**: any pointer type (e.g., `int*`, `char*`)
* **Value**: `nullptr` (C++11 and later)

* **Usage**
* Indicates that the pointer **does not point to any valid memory**
* Helps **avoid dangling pointers**

* **Example**

```cpp
int* ptr = nullptr;  // pointer points to nothing
if(ptr == nullptr) {
    // safe check before using ptr
}
```

#### **Important Points**
* `NULL` is older, `nullptr` is preferred in modern C++
* Always initialize pointers to `nullptr` if not assigned
* Dereferencing a null pointer → **runtime error**
---


###### operators
## 🔮 operator

### Categories
* **Arithmetic** → `+`, `-`, `*`, `/`, `%`
* **Relational** → `==`, `!=`, `<`, `>`, `<=`, `>=`
* **Logical** → `&&`, `||`, `!`
* **Bitwise** → `&`, `|`, `^`, `~`, `<<`, `>>`
* **Assignment** → `=`, `+=`, `-=`, `*=`, `/=`, `%=` …
* **Increment / Decrement** → `++`, `--`
* **Conditional / Ternary** → `?:`
* **Comma** → `,`
* **Pointer / Reference** → `*`, `&`, `->`
* **Member / Scope** → `.`, `::`


#### Operator Precedence & Associativity

| **Precedence** | **Operator**                                                                 | **Description**                  | **Associativity** |          
| -------------- | ---------------------------------------------------------------------------- | -------------------------------- | ----------------- | 
| 1              | `::`                                                                         | Scope resolution                 | Left → Right      |            
| 2              | `++`, `--`, `+`(unary), `-`(unary), `!`, `~`, `*`(dereference), `&`(address) | Unary operators                  | Right → Left      |            
| 3              | `*`, `/`, `%`                                                                | Multiplication, division, modulo | Left → Right      |           
| 4              | `+`, `-`                                                                     | Addition, subtraction            | Left → Right      |           
| 5              | `<<`, `>>`                                                                   | Bitwise shift                    | Left → Right      |           
| 6              | `<`, `<=`, `>`, `>=`                                                         | Relational                       | Left → Right      |            
| 7              | `==`, `!=`                                                                   | Equality                         | Left → Right      |            
| 8              | `&`                                                                          | Bitwise AND                      | Left → Right      |            
| 9              | `^`                                                                          | Bitwise XOR                      | Left → Right      |         
| 10             | `\|`                                                                         | Bitwise OR                       | Left → Right      |          
| 11             | `&&`                                                                         | Logical AND                      | Left → Right      |            
| 12             | `||`                                                                         | Logical OR                       | Left → Right      |        
| 13             | `?:`                                                                         | Ternary conditional              | Right → Left      |            
| 14             | `=`, `+=`, `-=`, `*=`, `/=`, `%=` …                                          | Assignment                       | Right → Left      |           
| 15             | `,`                                                                          | Comma                            | Left → Right      |           


#### Notes

* Higher precedence → evaluated first
* Associativity → resolves **operators with same precedence**
* binary operators have **right-to-left** associativity
* always use parentheses `()` to avoid ambiguity

---


###### panctuator
## 🔮 pancuators

* **Punctuators**: symbols used to **separate, group, or structure** code
* **Role**: define **syntax and program flow**
* **Do not perform operations** like operators


### Common Punctuators

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

###### barebones of cpp program
## 🧩 Barebones of C++ Program

### Program Structure

* Starts from `main()`
* Statements end with `;`

### Expressions

* Produce a value
* Example: `a + b`, `x > 5`

### Statements

* Perform actions
* Example: declaration, assignment, `if`, `cout`

### Comments

* `//` → single-line
* `/* */` → multi-line

### Blocks

* Defined using `{ }`
* Same braces = same scope
---


###### Data Types Overview
## 🧩 data type 

Data types specify **what kind of data** a variable can store and **how much memory** is allocated.

### Categories of Data Types

* **Primitive (Built-in):** `int`, `float`, `double`, `char`, `bool`, `void`
* **Derived:** array, pointer, reference, function
* **User-defined:** `struct`, `union`, `enum`, `class`, `typedef`, `using`
* **Library / STL Types:** `string`, `vector`, `map`, `set`


### Integer Data Types

| Data Type            | Size (bytes) | Range                                                   |
| -------------------- | ------------ | ------------------------------------------------------- |
| `char`               | 1            | −128 to 127                                             |
| `unsigned char`      | 1            | 0 to 255                                                |
| `short int`          | 2            | −32,768 to 32,767                                       |
| `unsigned short int` | 2            | 0 to 65,535                                             |
| `int`                | 4            | −2,147,483,648 to 2,147,483,647                         |
| `unsigned int`       | 4            | 0 to 4,294,967,295                                      |
| `long int`           | 8            | −9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |
| `unsigned long int`  | 8            | 0 to 18,446,744,073,709,551,615                         |
| `long long int`      | 8            | −9.22×10¹⁸ to 9.22×10¹⁸                                 |


### Floating-Point Data Types

| Data Type     | Size (bytes) | Range (Approx.)           |
| ------------- | ------------ | ------------------------- |
| `float`       | 4            | 1.2×10⁻³⁸ to 3.4×10³⁸     |
| `double`      | 8            | 2.3×10⁻³⁰⁸ to 1.7×10³⁰⁸   |
| `long double` | 16           | 3.4×10⁻⁴⁹³² to 1.1×10⁴⁹³² |


### Other Data Types

| Data Type | Size       |
| --------- | ---------- |
| `bool`    | 1 byte     |
| `void`    | No storage |


### Important Concepts

* Size and range are **compiler & system dependent**
* **Signed vs Unsigned** affects range
* **Memory alignment & padding** affect structure size
* **POD (Plain Old Data)** vs non-POD types
* **auto keyword** performs compile-time type deduction

---

###### Variables Constants
## 🧩 Variable & constants

A **variable** stores data whose value can change, while a **constant** stores fixed data.

### Variables

* **Declaration vs Definition**
* **Initialization vs Assignment**
* **Scope:** local, global, block, namespace
* **Lifetime & storage duration**
* **Linkage:** internal (`static`) / external (`extern`)

### Constants

* `const` → read-only after initialization
* `constexpr` → evaluated at **compile time**
* `volatile` → value may change unexpectedly
* `mutable` → allows modification in `const` objects

### 1️. `const`

Value cannot change after initialization.

```cpp
const int x = 10;
// x = 20; ❌ error
```

With pointer:

```cpp
const int* p;   // cannot modify value through pointer
```

### 2️. `constexpr`

Evaluated at compile time.

```cpp
constexpr int square(int x) {
    return x * x;
}

constexpr int val = square(5);  // computed at compile time
```

⚠ Must use constant expression.

### 3. `volatile`

Value may change unexpectedly (hardware, threads).

```cpp
volatile int flag;
```

Used in:

* Embedded systems
* Hardware registers
* Multi-threading signals

Prevents compiler optimization on that variable.

### 4. `mutable`

Allows modification inside `const` object.

```cpp
class Test {
public:
    mutable int count = 0;

    void update() const {
        count++;   // allowed because mutable
    }
};
```

Without `mutable` → ❌ error

| Keyword     | Meaning                         |
| ----------- | ------------------------------- |
| `const`     | Cannot change value             |
| `constexpr` | Known at compile time           |
| `volatile`  | May change unexpectedly         |
| `mutable`   | Can modify even in const object |

---


###### Type Modifiers
## 🧩 Type Modifiers

Type modifiers change the **range and storage size** of data types.

#### Common Modifiers

* `short`, `long`, `long long`
* `signed`, `unsigned`

#### Notes

* Valid combinations depend on the base type
* Overflow & underflow may cause **undefined behavior**
* Integer promotion occurs in expressions

---

###### Type Conversion Type Casting
## 🧩 Type Conversion Type Casting


Type conversion means changing one data type into another.

### Implicit Conversion (Automatic)

* Done by compiler automatically
* Also called **Type Promotion**
* May cause data loss (narrowing)

```cpp
int x = 5;
double y = x;   // int → double
```

⚠ Example of data loss:

```cpp
double d = 3.7;
int n = d;   // 3 (decimal lost)
```

### Explicit Conversion (Type Casting)

Done manually by programmer.

#### C-Style Cast (Old)

```cpp
int x = (int)3.5;
```

Not recommended in modern C++.

#### C++ Casts (Modern & Safe)

##### 1️. `static_cast`

Used for normal conversions.

```cpp
double d = 3.5;
int x = static_cast<int>(d);
```

##### 2️. `const_cast`

Adds or removes `const`.

```cpp
const int a = 10;
int* p = const_cast<int*>(&a);
```

##### 3️. `reinterpret_cast`

Low-level conversion (unsafe).

```cpp
int x = 65;
char* p = reinterpret_cast<char*>(&x);
```

##### 4️. `dynamic_cast`

Used in polymorphism (runtime check).

```cpp
dynamic_cast<Derived*>(basePtr);
```

## Important Concepts

### Narrowing Conversion

Losing data while converting large type → smaller type.

```cpp
double d = 9.8;
int x = d;  // data loss
```

### User-Defined Conversion

Conversion using class functions.

```cpp
class A {
public:
    A(int x) {}
};
```

### Conversion Constructor

Constructor with single parameter enables conversion.

```cpp
class A {
public:
    A(int x) {}
};
```

### `explicit` Keyword

Prevents automatic conversion.

```cpp
class A {
public:
    explicit A(int x) {}
};
```

Now implicit conversion won’t happen.


| Type             | Meaning                 |
| ---------------- | ----------------------- |
| Implicit         | Automatic conversion    |
| Explicit         | Programmer controlled   |
| static_cast      | Safe normal cast        |
| dynamic_cast     | Runtime cast            |
| reinterpret_cast | Unsafe low-level        |
| const_cast       | Modify const            |
| explicit         | Prevent auto conversion |



---

###### sizeof operator 
## 🧩 sizeof Operator

`sizeof` is a **compile-time operator** used to find memory size.

* Returns value in bytes
* Result type is `size_t`
* `sizeof(array)` ≠ `sizeof(pointer)`
* Structure padding affects result
* No side effects
* `sizeof(char) == 1`

#### 1. Returns value in bytes

```cpp
cout << sizeof(int) << endl;
```

If `int` = 4 bytes → output: `4`

#### 2. Result type is `size_t`

```cpp
size_t s = sizeof(double);
```

`size_t` is an unsigned integer type.

#### 3. `sizeof(array) ≠ sizeof(pointer)`

```cpp
int arr[5];
cout << sizeof(arr) << endl;      // 20 (5 × 4)

int* ptr = arr;
cout << sizeof(ptr) << endl;      // 8 (on 64-bit system)
```

* Array stores full memory
* Pointer stores only address

#### 4. Structure Padding Affects Result

```cpp
struct A {
    char c;   // 1 byte
    int x;    // 4 bytes
};

cout << sizeof(A);
```

You may expect 5 bytes,
But output is often **8 bytes** (because of padding for alignment).


#### 5. No Side Effects

```cpp
int x = 10;
cout << sizeof(x++);
```

Output:

```
4
```

But `x` remains `10`
Because `sizeof` does NOT evaluate the expression.

#### 6. `sizeof(char) == 1`

Always true in C++.

```cpp
cout << sizeof(char);   // always 1
```

##### Important :
* It is defined by standard.
* Even if system uses 8-bit, 16-bit etc, `char` is defined as 1 byte.

---

* **Padding** -> Extra unused bytes added               
* **Alignment** -> Rule that decides where data is placed

### 1. Structure Padding

Structure padding is the **extra unused memory** added by the compiler inside a structure to maintain proper alignment.

#### Why?

To make memory access faster.

#### Example:

```cpp
struct A {
    char c;   // 1 byte
    int x;    // 4 bytes
};
```

Expected: 5 bytes
Actual: 8 bytes (because of 3 padding bytes)


### 2. Memory Alignment

Memory alignment means:

> Data is stored at memory addresses that are multiples of their size.

For example:

* `int` (4 bytes) → stored at address divisible by 4
* `double` (8 bytes) → stored at address divisible by 8

This improves CPU performance.



---


###### Comments
## 🧩 Comments

Comments are used to **explain code** and are ignored by the compiler.

#### Types

* **Single-line:** `//`
* **Multi-line:** `/* */`

---

###### boile plate code

## 🧩 Boiler Plate Code

**Boilerplate code** is the **minimum required code** to run a C++ program.

### Standard C++ boilerplate:

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "hello world"
    return 0;
}
```

### Explanation:

* `#include <iostream>` → input/output
* `using namespace std;` → avoids writing `std::`
* `int main()` → program execution starts here
* `return 0;` → successful program end

📌 Without boilerplate → program won’t compile

---

###### next line
## 🧩 Next Line

To move output to the **next line**, C++ provides two methods:

### 1️. `endl`

```cpp
cout << "Hello" << endl;
```

* Adds new line
* Flushes output buffer (slower)

### 2️. `\n`

```cpp
cout << "Hello\n";
```

* Faster
* Preferred in competitive programming

📌 Both move cursor to next line

---

###### Escape Sequences
## 🧩 Escape Sequences 

Escape sequences are **special character combinations** used inside **character and string literals** to represent **non-printable or special characters**. <br>
They always start with a **backslash (`\`)**.

### Common Escape Sequences

| Escape | Meaning            |
| ------ | ------------------ |
| `\n`   | New line           |
| `\t`   | Horizontal tab     |
| `\v`   | Vertical tab       |
| `\b`   | Backspace          |
| `\r`   | Carriage return    |
| `\f`   | Form feed          |
| `\a`   | Alert (beep sound) |
| `\\`   | Backslash          |
| `\'`   | Single quote       |
| `\"`   | Double quote       |
| `\?`   | Question mark      |
| `\0`   | Null character     |

### Numeric Escape Sequences

* **Octal** → `\nnn` (e.g., `\101` → `A`)
* **Hexadecimal** → `\xhh` (e.g., `\x41` → `A`)
* **Unicode**:

  * `\uXXXX` (16-bit)
  * `\UXXXXXXXX` (32-bit)

### Important Concepts

* Used inside **single (`' '`) and double (`" "`) quotes**
* Interpreted at **compile time**
* Helpful in **formatting output**
* `\0` marks end of C-style strings
* Invalid escape sequences cause **compiler warnings**

* **Example**

```cpp
#include <iostream>
using namespace std;

int main(){
    cout << "new\nline" << endl ;
    cout << "horizontal\ttab" << endl ;
    cout << "vertical\vtab" << endl ;
    cout << "back\bspace" << endl ;
    cout << "carriage\rreturn" << endl ;
    cout << "Form\ffeed" << endl ;
    cout << "alert\a" << endl ;
    cout << "C:\\back\\Slash";
    cout << "single\'s quote" ;
    cout << "Double Quote\"Hello\"";
    cout << "\?";
    char arr[] = "null\0chracter";
    cout << arr;
return 0;
}
```

**Output**

```
new
line
horizontal      tab
vertical
tab
bacspace
returnge
Form
feed
alert
```

---
###### output and input
## 🧩 Output & Input

### Output → `cout`

Used to display data on screen.

```cpp
cout << "Hello World";
cout << x;
```

### Input → `cin`

Used to take input from user.

```cpp
cin >> x;
cin >> a >> b;
```

### Important rules:

* `>>` separates input by space
* `cin` stops at space (for strings)
* For full line input → use `getline()` <br>
<br>
Example:

```cpp
int n;
cin >> n;
cout << "Value: " << n;
```

---

###### header
# 🎗 Header Files 

Header files contain **declarations** (functions, classes, variables, macros) that are shared across multiple source files.
##### include Types
1️. Angle Brackets -> **Standard Header Files** #include <iostream> <br>
2️. Double Quotes -> **User-Defined Header Files** #include "file.h"


##### Purpose :
* Code reusability
* Faster development
* Better modularity
* Separation of declaration & definition

```cpp
#include<iostream>

int main() {
    std::cout << "hey saujanya";
    return 0;
}
```

## 🌿 Standard Header Files

Provided by the C++ Standard Library. <br>
Stored in system directories, Platform independent

#### Examples
* `<iostream>` → input/output
* `<string>` → string handling
* `<cmath>` → math functions
* `<vector>`, `<map>`, `<algorithm>` → STL
* `<cstdlib>`, `<cstdio>`, `<cstring>`

## 🌿 User-Defined Header Files

Created by the programmer for custom code.

### Syntax

```cpp
#include "myfile.h"
```

* Enclosed in **double quotes**
* Compiler searches **current directory first**
* Used to share functions/classes across files
* Should contain **declarations only**, not main logic
* `< >` → compiler searches standard library
* `" "` → compiler searches current folder first


✔ Function declarations
✔ Class declarations
✔ Macros
✔ Constants

❌ Should NOT contain `main()`
❌ Should NOT contain full logic (usually)


### example

#### 📄 `myfile.h`


```cpp
ifndef MYFILE_H
#define MYFILE_H

#include <iostream>
using namespace std ;

void greet() {
        cout << "Hello from header file!" << endl;
}

int add(int a, int b) {
    return a + b;
}

#endif
```

```cpp
#ifndef MYFILE_H
#define MYFILE_H
```

This is called a **header guard** <br>
It prevents multiple inclusion errors. <br>
Without guards → multiple definition error <br>
With guards → safe <br>



#### `main.cpp`

```cpp
#include <iostream>
#include "myfile.h"

using namespace std;

int main(){
    greet();                 // function call
    cout << add(5, 3);       // function call
    return 0;
}
```

### How Compilation Works

If using terminal:

```bash
g++ main.cpp myfile.cpp -o program
./program
```

Compiler links both files together.

---



## 🌿 using namespace std

Used to avoid writing `std::` repeatedly.

#### Example
```cpp
using namespace std;
cout << "Hello";
```

* Saves typing
* Should be **avoided in large projects**
* Can cause **name conflicts**
* Better alternative:

```cpp
std::cout << "Hello";
```

### Namespace Creation

Namespaces group identifiers to avoid **name collision**.

#### Syntax

```cpp
namespace MySpace {
    int x = 10;
}
```

#### Usage

```cpp
MySpace::x;
```

## 🌿 Scope Resolution Operator `::`

Used to access:

* Namespace members
* Class members
* Global variables
* Static class members

#### Examples

```cpp
std::cout << "Hello";
MySpace::x;
ClassName::function();
::globalVar;
```


## 🌿 competitive programming 
**#include <bits/stdc++.h>** is a non-standard header that includes almost all standard C++ libraries at once.

* It is mainly used in competitive programming.
* It pulls in headers like: <iostream>, <vector>, <algorithm>, <map>, <set>, <stack>, <queue>, <cmath> <br>
So you don’t need to include each one separately.


❌ **Libraries it does **NOT** include**

1. **Non-standard / compiler-specific headers**

These are outside the C++ standard:

* `<windows.h>`
* `<conio.h>`
* `<unistd.h>`
* `<dos.h>`

Reason: They are **OS/compiler specific**, not C++ STL.


2. **C headers without `c` prefix (sometimes)**

It includes:

* `<cstdio>`, `<cstring>`, `<cmath>`

But **not guaranteed** to include:

* `<stdio.h>`
* `<string.h>`
* `<math.h>`

(Use the `c` versions in C++)


 3. **Graphics / GUI libraries**

* `<graphics.h>`
* `<SFML/*>`
* `<GL/gl.h>`
* `<SDL.h>`

These are **external libraries**, not STL.

4. **Threading / system-level libraries (sometimes missing)**

May not reliably include:

* `<thread>`
* `<mutex>`
* `<condition_variable>`
* `<atomic>`

(Some GCC versions include them, some don’t → **not safe to rely on**)


5. **Networking / modern C++ libs**

* `<asio>`
* `<boost/*>` (Boost is external)


## 🌿 C++ Standard Header Files 


### Input / Output

| Header           | Purpose              | Important Components                             |
| ---------------- | -------------------- | ------------------------------------------------ |
| **`<iostream>`** | Standard I/O streams | `cin`, `cout`, `cerr`, `clog`                    |
| **`<iomanip>`**  | Output formatting    | `setw()`, `setprecision()`, `fixed`, `setfill()` |
| **`<fstream>`**  | File handling        | `ifstream`, `ofstream`, `fstream`                |
| **`<sstream>`**  | String streams       | `stringstream`, `istringstream`, `ostringstream` |


### Strings & Characters

| Header          | Purpose            | Important Components                        |
| --------------- | ------------------ | ------------------------------------------- |
| **`<string>`**  | String handling    | `string`, `getline()`, `substr()`, `find()` |
| **`<cstring>`** | C-style strings    | `strlen()`, `strcpy()`, `strcmp()`          |
| **`<cctype>`**  | Character handling | `isalpha()`, `isdigit()`, `toupper()`       |
| **`<cwchar>`**  | Wide characters    | `wchar_t`, wide string functions            |


### Containers (STL)

| Header                | Purpose            | Important Components              |
| --------------------- | ------------------ | --------------------------------- |
| **`<vector>`**        | Dynamic array      | `vector`, `push_back()`, `size()` |
| **`<array>`**         | Fixed-size array   | `array`, `at()`                   |
| **`<deque>`**         | Double-ended queue | `deque`, `push_front()`           |
| **`<list>`**          | Doubly linked list | `list`, `push_back()`             |
| **`<forward_list>`**  | Singly linked list | `forward_list`                    |
| **`<set>`**           | Ordered set        | `set`, `multiset`                 |
| **`<unordered_set>`** | Hash set           | `unordered_set`                   |
| **`<map>`**           | Key-value pairs    | `map`, `multimap`                 |
| **`<unordered_map>`** | Hash map           | `unordered_map`                   |
| **`<stack>`**         | Stack container    | `stack`, `push()`, `pop()`        |
| **`<queue>`**         | Queue container    | `queue`, `priority_queue`         |


### Algorithms & Utilities

| Header             | Purpose          | Important Components            |
| ------------------ | ---------------- | ------------------------------- |
| **`<algorithm>`**  | Algorithms       | `sort()`, `reverse()`, `find()` |
| **`<numeric>`**    | Numeric ops      | `accumulate()`, `gcd()`         |
| **`<functional>`** | Function objects | `function`, `greater<>`         |
| **`<iterator>`**   | Iterators        | `advance()`, `next()`           |
| **`<utility>`**    | Utility          | `pair`, `make_pair()`, `swap()` |


### Math & Numbers

| Header          | Purpose         | Important Components                  |
| --------------- | --------------- | ------------------------------------- |
| **`<cmath>`**   | Math functions  | `sqrt()`, `pow()`, `abs()`            |
| **`<complex>`** | Complex numbers | `complex`, `real()`, `imag()`         |
| **`<random>`**  | Random numbers  | `mt19937`, `uniform_int_distribution` |
| **`<limits>`**  | Type limits     | `numeric_limits`                      |


### Memory Management

| Header          | Purpose           | Important Components                        |
| --------------- | ----------------- | ------------------------------------------- |
| **`<memory>`**  | Smart pointers    | `unique_ptr`, `shared_ptr`, `make_unique()` |
| **`<new>`**     | Memory allocation | `operator new`, `bad_alloc`                 |
| **`<cstdlib>`** | C utilities       | `malloc()`, `free()`                        |


### 🔹 Exception Handling

| Header            | Purpose             | Important Components           |
| ----------------- | ------------------- | ------------------------------ |
| **`<exception>`** | Base exceptions     | `exception`, `bad_exception`   |
| **`<stdexcept>`** | Standard exceptions | `runtime_error`, `logic_error` |
| **`<typeinfo>`**  | RTTI                | `typeid`                       |


### Time & Date

| Header         | Purpose          | Important Components       |
| -------------- | ---------------- | -------------------------- |
| **`<chrono>`** | Time library     | `system_clock`, `duration` |
| **`<ctime>`**  | C time functions | `time()`, `clock()`        |


### Multithreading & Concurrency

| Header                     | Purpose           | Important Components         |
| -------------------------- | ----------------- | ---------------------------- |
| **`<thread>`**             | Threads           | `thread`, `this_thread`      |
| **`<mutex>`**              | Mutex locking     | `mutex`, `lock_guard`        |
| **`<atomic>`**             | Atomic operations | `atomic<int>`                |
| **`<future>`**             | Async             | `async`, `future`, `promise` |
| **`<condition_variable>`** | Thread sync       | `condition_variable`         |


### Type Traits & Compile-Time

| Header              | Purpose          | Important Components   |
| ------------------- | ---------------- | ---------------------- |
| **`<type_traits>`** | Type info        | `is_same`, `enable_if` |
| **`<concepts>`**    | Concepts (C++20) | `integral`, `concept`  |
| **`<bitset>`**      | Bit manipulation | `bitset`               |


### C Compatibility Headers (C → C++)

| C Header   | C++ Version |
| ---------- | ----------- |
| `stdio.h`  | `<cstdio>`  |
| `stdlib.h` | `<cstdlib>` |
| `string.h` | `<cstring>` |
| `math.h`   | `<cmath>`   |
| `ctype.h`  | `<cctype>`  |

---


















###### Data handling
# 🎗 Data Handling 

* **Data Handling**
* **Data handling** refers to **storing, processing, and manipulating data** in a program.
* C++ handles data using **data types, variables, constants, and operators**.

#### classification
 1. Built-in (Core / Primitive)
 2. Derived
 3. User-defined

### Core (Built-in) Data Types
Characteristics : <br>
* Predefined in C++
* Fast and memory-efficient
* Store **single values**

## Core Data Types – Flow Chart (Hierarchy)

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

## Numeric Data Types

### Integer Types

* Used to store **whole numbers**
* No decimal point

| Type            | Description          |
| --------------- | -------------------- |
| `int`           | Standard integer     |
| `short int`     | Smaller range        |
| `long int`      | Larger range         |
| `long long int` | Very large numbers   |
| `unsigned int`  | Only positive values |

### Floating-Point Types

* Used to store **decimal numbers**

| Type          | Precision          |
| ------------- | ------------------ |
| `float`       | Single precision   |
| `double`      | Double precision   |
| `long double` | Extended precision |

### Character Data Type

#### `char`

* Stores **single character**
* Written in **single quotes**
* Size: **1 byte**
* Stored using **ASCII values**

Examples:

* `'A'`, `'9'`, `'@'`

### Boolean Data Type

#### `bool`

* Stores **true / false**
* Used in **conditions and decisions**
* Internally:

  * `true` → 1
  * `false` → 0

### Void Data Type

#### `void`

* Represents **no value**
* Used when:

  * Function returns nothing
  * Generic pointers

## Mutable vs Immutable Data (C++ Perspective)

> C++ does **not strictly enforce** mutability like Python, but conceptually:


#### Mutable Data

* Data that **can be changed**
* Examples:
  * Variables
  * Arrays
  * Objects
  * `string` (STL) <br>
Value can be modified after creation

#### Immutable Data

* Data that **cannot be changed once created**
* Achieved using:
  * `const` keyword
  * Literal values <br>
Prevents accidental modification

## Derived Data Types

* Formed using **core data types**

| Type      | Description             |
| --------- | ----------------------- |
| Array     | Collection of same type |
| Pointer   | Stores address          |
| Reference | Alias of variable       |
| Function  | Block of code           |


## User-Defined Data Types

* Created by programmer

| Type                | Purpose               |
| ------------------- | --------------------- |
| `struct`            | Group different types |
| `union`             | Shared memory         |
| `enum`              | Named constants       |
| `typedef` / `using` | Alias for data type   |
| `class`             | Blueprint for objects |

---


















##### flow of control
# 🎗 Flow of Control  

Flow of control refers to the **order in which statements in a C++ program are executed**. By default, execution is **sequential (top to bottom)**, but flow-control statements allow us to change this order based on **conditions, loops, or jumps**.

## Types of Flow of Control in C++

C++ flow of control is broadly classified into:

1. **Sequential Statements**
2. **Decision Making / Conditional Statements**
3. **Looping / Iteration Statements**
4. **Jump Statements**

## 1. Sequential Control

* Statements execute **one after another** in the order written.
* No condition or repetition involved.

Example:

```cpp
int a = 10;
int b = 20;
int c = a + b;
```

## 2. Decision Making Statements

Used to **execute statements based on conditions**.

### 2.1 if Statement

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

### 2.2 if–else Statement

* Executes one block if condition is true, otherwise another.

Syntax:

```cpp
if (condition) {
    // true block
} else {
    // false block
}
```

### 2.3 if–else if–else Ladder

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


### 2.4 Nested if

* An if statement inside another if.

Example:

```cpp
if (a > b) {
    if (a > c) {
        cout << "A is largest";
    }
}
```

### 2.5 switch Statement

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

## 3. Looping Statements

Used to **repeat a block of code** multiple times.

### Types of Loops:

1. while loop
2. do–while loop
3. for loop


### 3.1 while Loop (Entry Controlled)

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

### 3.2 do–while Loop (Exit Controlled)

* Loop body executes **at least once**.

Syntax:

```cpp
do {
    // loop body
} while (condition);
```

### 3.3 for Loop

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


## Nested Loops

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

## 4. Jump Statements

Used to **transfer control abruptly**.

### 4.1 break

* Terminates loop or switch immediately.

```cpp
break;
```

### 4.2 continue

* Skips current iteration and moves to next.

```cpp
continue;
```

### goto (Not Recommended)

* Transfers control to a labeled statement.

Syntax:

```cpp
goto label;
...
label:
```

Reason to avoid:

* Makes code **hard to read and debug**

### return

* Exits from a function and returns value.

```cpp
return 0;
```


## Conditional Operator (Ternary Operator)

* Short form of if–else.

Syntax:

```cpp
(condition) ? expr1 : expr2;
```

Example:

```cpp
int max = (a > b) ? a : b;
```

## Infinite Loops

A loop that **never terminates**.

Example:

```cpp
while (true) {
}
```
---













###### function
# 🎗 Functions 

A **function** is a block of code that performs a specific task and can be reused multiple times.

## Function Declaration & Definition

### Declaration (Prototype)

* Tells compiler about function **name, return type, parameters**
* No body included

```cpp
int add(int, int);
```

### Definition

* Contains the actual **implementation**

```cpp
int add(int a, int b) {
    return a + b;
}
```

### Notes

* Declaration must appear **before function call**
* Multiple declarations allowed, **one definition only**

---

## Function Call

Used to execute a function.

```cpp
int result = add(2, 3);
```

### Points

* Arguments are copied or referenced based on call type
* Control returns after function execution


## Return Type

Specifies the type of value returned by the function.

```cpp
int sum();
```

### Notes

* `return` statement ends function execution
* Only **one value** can be returned (multiple via structures / references)
* `return;` used in `void` functions

## Void Functions

Functions that **do not return any value**.

```cpp
void display() {
    cout << "Hello";
}
```

### Use Case

* Printing, updating global variables, performing actions

## Call by Value

* Copy of actual argument is passed
* Changes **do not affect original value**

```cpp
void fun(int x);
```

### Pros / Cons

✔ Safe
✖ Extra memory & time


## Call by Reference

* Reference (address) is passed
* Changes **affect original variable**

```cpp
void fun(int &x);
```

### Notes

* Faster
* Used for swapping, updating values
* Pointer-based reference also possible

## Default Arguments

Provide default values to parameters.

```cpp
int add(int a, int b = 10);
```

### Rules

* Default arguments must be **from right to left**
* Defined only once (usually in prototype)

## Inline Functions

Replaces function call with function code.

```cpp
inline int square(int x) {
    return x * x;
}
```

### Notes

* Reduces function call overhead
* Used for **small functions**
* Compiler may ignore `inline`


## Function Overloading

Multiple functions with **same name but different parameters**.

```cpp
int add(int a, int b);
float add(float a, float b);
```

### Rules

* Different number or type of parameters
* Return type alone is **not sufficient**
* Achieves **compile-time polymorphism**


## Recursion

A function calling itself to solve a problem.

```cpp
int fact(int n) {
    if(n == 0) return 1;
    return n * fact(n - 1);
}
```

### Key Concepts

* **Base condition** (mandatory)
* Uses **stack memory**
* Can cause stack overflow if not controlled















###### pointer
# 🎗 Pointers 

A **pointer** is a variable that stores the **address of another variable**.

## Pointer Declaration & Initialization

```cpp
int a = 10;
int *p = &a;
```

* `*` → pointer variable
* `&` → address-of operator
* Pointer must match the **data type** it points to

## Dereferencing Pointer

```cpp
cout << *p;
```

* `*p` accesses the **value at the stored address**
* Dereferencing an uninitialized pointer causes **undefined behavior**


## Types of Pointers

### 1️. Null Pointer

```cpp
int *p = NULL;   // or nullptr (preferred)
```

* Points to nothing
* Prevents accidental access

### 2️. Void Pointer

```cpp
void *p;
```

* Can store address of any type
* Must be **type-cast before dereferencing**

### 3️. Wild Pointer

* Declared but **not initialized**
* Dangerous, may crash program

### 4️. Dangling Pointer

* Points to memory that has been **freed**
* Causes runtime errors

## Pointer Arithmetic

* `p + 1` → moves by **size of data type**
* Valid only within **array bounds**

```cpp
p++;
p--;
```

## Pointer & Arrays

* Array name is a **constant pointer**

```cpp
int a[5];
int *p = a;
```

* `a[i] == *(a + i)`

## Pointer to Pointer

```cpp
int **pp;
```

* Stores address of another pointer
* Used in **dynamic memory & 2D arrays**

## Call by Reference using Pointers

```cpp
void swap(int *a, int *b);
```

* Changes affect original variables
* Used for efficiency

## Dynamic Memory Allocation

```cpp
int *p = new int;
delete p;
```

* Allocated at **runtime**
* `new` → allocate
* `delete` → deallocate

## Smart Pointers (Modern C++)

* `unique_ptr`
* `shared_ptr`
* `weak_ptr`

✔ Automatic memory management
✔ Prevent memory leaks

## Common Mistakes (Exam Traps)

* Dereferencing NULL pointer
* Memory leak (missing `delete`)
* Using freed pointer
* Wrong pointer type

## Advantages of Pointers

* Efficient memory usage
* Dynamic memory handling
* Used in data structures (LL, Tree, Graph)
* Enables call by reference

## Disadvantages

* Complex syntax
* Error-prone
* Security risks if misused
---













###### dynamic memory allocation
# 🎗 Dynamic Memory Allocation 

Dynamic Memory Allocation (DMA) allows memory to be **allocated and deallocated at runtime**, instead of compile time.

## Why Dynamic Memory Allocation?

* Size not known at compile time
* Efficient memory usage
* Required for **data structures** (Linked List, Tree, Graph)
* Memory allocated from **Heap**

## Memory Areas (Important)

| Area  | Purpose                          |
| ----- | -------------------------------- |
| Stack | Function calls, local variables  |
| Heap  | Dynamic memory (`new`, `delete`) |
| Data  | Global & static variables        |
| Code  | Program instructions             |

## `new` Operator

Allocates memory dynamically and returns its address.

### Syntax

```cpp
int *p = new int;
```

### Initialization

```cpp
int *p = new int(10);
```

### Notes

* Returns pointer of required type
* Constructor is called (for objects)
* Throws exception on failure

## `delete` Operator

Frees dynamically allocated memory.

### Syntax

```cpp
delete p;
```

### Important

* Prevents memory leak
* Pointer becomes **dangling** after delete


## Dynamic Array Allocation

```cpp
int *arr = new int[n];
```

### Deallocation

```cpp
delete[] arr;
```

### Notes

* Use `delete[]` for arrays
* `new[]` calls constructors for all elements

## `new` vs `malloc`

| Feature      | new           | malloc     |
| ------------ | ------------- | ---------- |
| Language     | C++           | C          |
| Type-safe    | Yes           | No         |
| Constructor  | Called        | Not called |
| Return type  | Typed pointer | `void*`    |
| Deallocation | delete        | free       |

## `delete` vs `free`

* `delete` → used with `new`
* `free` → used with `malloc`
* Mixing them causes **undefined behavior**

## Smart Pointers (Modern C++)

Automatically manage dynamic memory.

### Types

* `unique_ptr` → single ownership
* `shared_ptr` → shared ownership
* `weak_ptr` → non-owning reference

### Advantage

✔ No memory leaks
✔ Exception safe

## Common Errors (Exam Traps)

* Memory leak (no delete)
* Dangling pointer
* Double delete
* Using deleted memory
* Using `delete` instead of `delete[]`

## Advantages of DMA

* Efficient memory utilization
* Flexible data size
* Essential for advanced data structures

## Disadvantages

* Manual management needed
* Slower than stack allocation
* Risk of memory leaks

## Example

```cpp
int n;
cin >> n;
int *arr = new int[n];
// use array
delete[] arr;
```















###### Structures Unions
# 🎗 Structures & Unions 

**Structure (`struct`)**
A **structure** is a **user-defined data type** that groups **different data types** under one name.

### Syntax

```cpp
struct Student {
    int roll;
    float marks;
};
```

### Key Points

* Members have **separate memory**
* Accessed using **dot (`.`) operator**
* Can contain **functions (methods)** in C++
* Supports **arrays, pointers, nesting**
* Objects can be created like classes


## Structure Features

* Memory allocated = **sum of all members**
* Supports **data abstraction**
* Can be passed to functions
* Can be returned from functions
* Can use **typedef / using**

```cpp
Student s1;
```

## Union (`union`)

A **union** is a user-defined data type where **all members share the same memory location**.

### Syntax

```cpp
union Data {
    int i;
    float f;
};
```

### Key Points

* Only **one member usable at a time**
* Memory allocated = **size of largest member**
* Saves memory
* Writing one member overwrites others


## Structure vs Union (Important Table)

| Feature     | Structure                | Union               |
| ----------- | ------------------------ | ------------------- |
| Memory      | Separate for each member | Shared memory       |
| Size        | Sum of members           | Largest member      |
| Access      | All members at once      | One at a time       |
| Data safety | High                     | Low                 |
| Use case    | Complex data             | Memory optimization |


## Accessing Members

```cpp
s1.roll = 10;
```

For pointers:

```cpp
Student *p;
p->roll = 10;
```


## Nested Structure / Union

```cpp
struct Address {
    int pin;
};

struct Student {
    Address addr;
};
```


## Structure with Functions

```cpp
struct Test {
    int x;
    void show() {
        cout << x;
    }
};
```


## Typedef / using with Structure

```cpp
typedef struct Student {
    int roll;
} Stu;
```

OR

```cpp
using Stu = Student;
```


## When to Use What?

* Use **structure** when:

  * Multiple values needed together
  * Data safety important

* Use **union** when:

  * Memory is limited
  * Only one value needed at a time


## Exam & Interview Traps

* Union members overwrite each other
* Structure size affected by **padding**
* C++ struct = class (default public)
* Union cannot have non-static data members with constructors (older C++)


## Advantages

### Structure

✔ Organized data
✔ Easy data handling

### Union

✔ Memory efficient

---












##### exception handling
# 🎗 Exception Handling 

**Exception Handling** is a mechanism to handle **runtime errors** and maintain **normal program flow**.

## Why Exception Handling?

* Prevents abnormal program termination
* Separates **error-handling code** from logic
* Improves reliability & debugging


## Keywords Used

| Keyword | Purpose                         |
| ------- | ------------------------------- |
| `try`   | Wraps code that may cause error |
| `catch` | Handles exception               |
| `throw` | Generates exception             |


## Basic Syntax

```cpp
try {
    // risky code
    throw 10;
}
catch(int e) {
    cout << e;
}
```


## Flow of Control

1. Code inside `try` executes
2. Exception occurs → `throw`
3. Control jumps to matching `catch`
4. Remaining `try` code is skipped


## Multiple Catch Blocks

```cpp
try {
    throw 5.5;
}
catch(int e) { }
catch(double d) { }
catch(...) { }   // default catch
```

### Rules

* Order matters (derived → base)
* `catch(...)` must be last


## Catch All Handler

```cpp
catch(...) {
    cout << "Unknown Exception";
}
```

* Handles all types
* Used as fallback


## User-Defined Exceptions

### Using Class

```cpp
class MyException {
};

try {
    throw MyException();
}
catch(MyException e) {
    cout << "Custom Exception";
}
```


## Throwing Objects

```cpp
throw runtime_error("Error occurred");
```

* Supports object-oriented error handling


## Standard Exception Classes (`<exception>`)

| Class           | Meaning                   |
| --------------- | ------------------------- |
| `exception`     | Base class                |
| `runtime_error` | Runtime error             |
| `logic_error`   | Logical error             |
| `bad_alloc`     | Memory allocation failure |


## Re-throwing an Exception

```cpp
catch(...) {
    throw;
}
```

* Sends exception to outer `catch`


## Nested try-catch

```cpp
try {
    try {
        throw 1;
    }
    catch(int e) {
        throw;
    }
}
catch(int e) {
    cout << "Handled";
}
```


## Exception vs Error

| Exception      | Error             |
| -------------- | ----------------- |
| Recoverable    | Not recoverable   |
| Runtime        | Compile/system    |
| Can be handled | Cannot be handled |


## Stack Unwinding

* Automatic destruction of local objects
* Happens when exception is thrown
* Ensures no memory leaks


## Destructor & Exception

* Destructors are called during stack unwinding
* Never throw exceptions from destructors


## Function Exception Specification (Deprecated)

```cpp
void fun() throw(int);
```

❌ Avoid — replaced by `noexcept`


## `noexcept`

```cpp
void fun() noexcept;
```

* Guarantees no exception
* Improves optimization


## Exception Handling Best Practices

✔ Throw by value
✔ Catch by reference
✔ Avoid using exceptions for flow control
✔ Handle resources using RAII


## Common Traps (Exam)

* `catch` without `try` ❌
* Base class `catch` before derived ❌
* Ignoring `catch(...)`
* Throwing pointer instead of object


## Real-World Example

* Division by zero
* File not found
* Memory allocation failure


## Short Definition (1-Line)

> Exception handling is a technique to handle runtime errors using `try`, `catch`, and `throw`.












##### file handling
# 🎗 File Handling 

**File Handling** allows a program to **store data permanently** in files and **retrieve it later**.

## Why File Handling?

* Data persistence
* Large data storage
* Data sharing between programs
* Backup & recovery

## Header File

```cpp
#include <fstream>
```


## File Stream Classes

| Class      | Purpose        |
| ---------- | -------------- |
| `ifstream` | Read from file |
| `ofstream` | Write to file  |
| `fstream`  | Read + Write   |


## File Object Creation

```cpp
ifstream fin;
ofstream fout;
fstream file;
```

## Opening a File

### Method 1: Constructor

```cpp
ofstream fout("data.txt");
```

### Method 2: `open()`

```cpp
fout.open("data.txt");
```


## Closing a File

```cpp
fout.close();
```

✔ Always close to avoid data loss


## Writing to a File

```cpp
ofstream fout("data.txt");
fout << "Hello File";
```


## Reading from a File

### Using `>>`

```cpp
ifstream fin("data.txt");
string s;
fin >> s;
```

### Using `getline()`

```cpp
getline(fin, s);
```


## File Open Modes

| Mode          | Meaning             |
| ------------- | ------------------- |
| `ios::in`     | Read                |
| `ios::out`    | Write               |
| `ios::app`    | Append              |
| `ios::ate`    | Move pointer to end |
| `ios::trunc`  | Clear file          |
| `ios::binary` | Binary mode         |

### Example

```cpp
fstream file("data.txt", ios::in | ios::out);
```

## Append vs Write

* `ios::out` → overwrites
* `ios::app` → adds data at end


## Checking File Open Status

```cpp
if(!file) {
    cout << "File not opened";
}
```


## End of File (EOF)

```cpp
while(!fin.eof()) {
    fin >> s;
}
```

⚠ `eof()` becomes true **after** reading fails


## File Pointers

| Pointer | Purpose       |
| ------- | ------------- |
| `get`   | Read pointer  |
| `put`   | Write pointer |


## Pointer Functions

```cpp
file.seekg(pos);   // move read pointer
file.seekp(pos);   // move write pointer
file.tellg();      // current read position
file.tellp();      // current write position
```


## Random Access in File

```cpp
file.seekg(5);
file.seekp(10);
```

✔ Used in binary files


## Binary File Handling

```cpp
ofstream fout("data.bin", ios::binary);
```

### Writing Object

```cpp
fout.write((char*)&obj, sizeof(obj));
```

### Reading Object

```cpp
fin.read((char*)&obj, sizeof(obj));
```


## Text File vs Binary File

| Text File      | Binary File      |
| -------------- | ---------------- |
| Human readable | Machine readable |
| Slow           | Fast             |
| Larger size    | Smaller size     |


## File Handling with Objects

* Direct storage of objects
* Used in databases
* Requires binary mode


## Error Handling in Files

* File not found
* Permission denied
* Disk full

Use:

```cpp
if(file.fail())
```



## Common Mistakes (Exam)

❌ Forgetting `close()`
❌ Using wrong open mode
❌ Using `eof()` incorrectly
❌ Mixing text & binary modes


## Real-Life Uses

* Student records
* Log files
* Configuration files
* Databases


## One-Line Definition

> File handling is the process of storing and retrieving data permanently using files.


## Diagram (Conceptual)

```
Program → File Stream → File
```







##### templates
# 🎗 Templates 

**Templates** allow writing **generic programs**, so the **same code works for different data types**.

## Why Templates?

* Avoid code duplication
* Type-safe generic programming
* Reusability
* Faster development


## Types of Templates

1. **Function Templates**
2. **Class Templates**


## Function Templates

### Definition

A **function template** works for **any data type**.

### Syntax

```cpp
template <class T>
T add(T a, T b) {
    return a + b;
}
```

### Usage

```cpp
add<int>(2, 3);
add<float>(2.5, 3.5);
```

✔ Compiler generates **separate functions** for each type


## Template Parameters

```cpp
template <typename T>
```

`class` and `typename` are **same**


## Multiple Template Parameters

```cpp
template <class T, class U>
void display(T a, U b) {
    cout << a << " " << b;
}
```

## Class Templates

### Syntax

```cpp
template <class T>
class Box {
    T data;
public:
    Box(T d) {
        data = d;
    }
    void show() {
        cout << data;
    }
};
```

### Object Creation

```cpp
Box<int> b1(10);
Box<float> b2(5.5);
```


## Default Template Arguments

```cpp
template <class T = int>
class Sample {
    T x;
};
```

Usage:

```cpp
Sample<> s;     // int
Sample<float> f;
```


## Template Specialization

Used to **change behavior for a specific type**

### Function Specialization

```cpp
template <>
void display<int>(int a) {
    cout << "Integer: " << a;
}
```


### Class Specialization

```cpp
template <>
class Box<char> {
public:
    void show() {
        cout << "Char Box";
    }
};
```


## Partial Specialization (Class Only)

```cpp
template <class T, class U>
class Test { };

template <class T>
class Test<T, int> { };
```

✔ Not allowed for function templates


## Template Overloading

Templates can be **overloaded like functions**

```cpp
template <class T>
void fun(T a);

void fun(int a);
```

✔ Non-template has higher priority


## Compile-Time Polymorphism

Templates achieve **compile-time polymorphism**

✔ Faster than run-time
✔ No virtual table


## Template vs Macro

| Template            | Macro         |
| ------------------- | ------------- |
| Type-safe           | Not type-safe |
| Checked by compiler | No checking   |
| Debuggable          | Hard to debug |


## STL & Templates

STL containers use templates:

```cpp
vector<int>
map<int, string>
```


## Hidden / Advanced Concepts

### ✔ Template Instantiation

* Compiler creates code when used

### ✔ Code Bloat

* Too many types → larger executable

### ✔ Header-Only Templates

* Templates must be in `.h` file


## Common Errors (Exam)

❌ Missing `< >` while object creation
❌ Defining template functions in `.cpp`
❌ Confusing specialization with overloading


## One-Line Definition (Exam)

> Templates enable generic programming by allowing functions and classes to operate with any data type.


## Very Important Questions

* Why templates are header-only?
* Difference between template and function overloading
* Template specialization vs overloading
* Why partial specialization not allowed for functions?


## Diagram (Concept)

```
Template Code
     ↓
Compiler Instantiation
     ↓
Type-Specific Code
```












#### advanced concept
# 🎗 Advanced C++ Concepts


## 1️. Lambda Expressions

### Definition

Anonymous (unnamed) functions used for **short operations**.

### Syntax

```cpp
[capture](parameters) -> return_type {
    body;
};
```

### Example

```cpp
auto sum = [](int a, int b) {
    return a + b;
};
```

### Capture List

| Capture | Meaning                  |
| ------- | ------------------------ |
| `[ ]`   | No capture               |
| `[=]`   | Capture all by value     |
| `[&]`   | Capture all by reference |
| `[x]`   | Capture x by value       |
| `[&x]`  | Capture x by reference   |

✔ Used heavily in **STL algorithms**


## 2️. Smart Pointers

### Why?

Avoid **memory leaks** and **dangling pointers**

### Types of Smart Pointers

| Pointer      | Ownership            |
| ------------ | -------------------- |
| `unique_ptr` | Single owner         |
| `shared_ptr` | Multiple owners      |
| `weak_ptr`   | Non-owning reference |


### unique_ptr

```cpp
unique_ptr<int> p = make_unique<int>(10);
```

✔ Cannot be copied
✔ Can be moved


### shared_ptr

```cpp
shared_ptr<int> p1 = make_shared<int>(10);
shared_ptr<int> p2 = p1;
```

✔ Reference counting


### weak_ptr

* Prevents **circular dependency**
* No ownership


## 3️. Move Semantics

### Why?

Avoid **deep copy** → improves performance


### Move Constructor

```cpp
MyClass(MyClass&& obj);
```

✔ Uses **rvalue references (`&&`)**
✔ Transfers resources


### std::move

```cpp
obj2 = std::move(obj1);
```

✔ Converts lvalue → rvalue

## 4️. auto Keyword

### Purpose

Compiler **automatically deduces data type**

```cpp
auto x = 10;
auto y = 5.5;
```

✔ Mandatory with lambdas iterators
❌ Cannot be used without initialization


## 5️. constexpr

### Meaning

Value evaluated at **compile time**

```cpp
constexpr int square(int x) {
    return x * x;
}
```

✔ Faster execution
✔ Used for constants & functions


## 6️. mutable Keyword

### Purpose

Allows modification inside **const object**

```cpp
class Test {
    mutable int x;
public:
    void change() const {
        x++;
    }
};
```

✔ Breaks const restriction safely


## 7️. friend Keyword

### Meaning

Allows **non-member access to private data**

### Friend Function

```cpp
friend void show(Test&);
```

### Friend Class

```cpp
friend class Demo;
```

✔ Friendship is **not inherited**
✔ Not transitive

## 8️. nullptr

### Why?

Replaces `NULL`

```cpp
int* p = nullptr;
```

✔ Type-safe
✔ Avoids ambiguity


## 9️. enum class (Scoped Enum)

```cpp
enum class Color { Red, Blue };
```

✔ Strongly typed
✔ Avoids name conflicts


## 10. Deleted & Default Functions

```cpp
Test() = default;
Test(const Test&) = delete;
```

✔ Control object behavior
✔ Important for safety


## Compile-Time vs Run-Time

| Feature          | Time    |
| ---------------- | ------- |
| Templates        | Compile |
| Inline           | Compile |
| Virtual Function | Run     |


## Hidden Exam Points

✔ Lambdas are **function objects**
✔ Smart pointers are in `<memory>`
✔ Move semantics reduces copy overhead
✔ constexpr ≠ const


## One-Line Exam Definition

> Advanced C++ concepts enhance performance, safety, and expressiveness of programs.


## Very Important Questions

* Difference: auto vs decltype
* shared_ptr vs unique_ptr
* Move vs copy constructor
* constexpr vs const
* Why weak_ptr is needed?

---












###### Competitive Programmings
# 🎗 Competitive Programming / DSA Readiness (Google-Level Notes)


## 1️. Time Complexity (Big-O Thinking)

### What Google Cares About

→ **Scalability**, not syntax

✔ Focus on **worst-case**
✔ Ignore constants & lower terms
✔ Understand how input grows

### Common Orders

```
O(1) < O(log n) < O(n) < O(n log n) < O(n²) < O(2ⁿ)
```

### Google Tip

> If your solution is worse than **O(n log n)**, rethink.



## 2️. Space Complexity (Memory Awareness)

### Types

* **Auxiliary space** (extra memory)
* **Stack space** (recursion)

✔ In-place preferred
✔ Avoid unnecessary arrays

### Example

```cpp
Merge Sort → O(n) space
Quick Sort → O(log n) stack
```


## 3️. Recursion vs Iteration (Production View)

| Recursion              | Iteration     |
| ---------------------- | ------------- |
| Cleaner                | Faster        |
| Risk of stack overflow | Memory safe   |
| Used in trees/graphs   | Used in loops |

✔ Google prefers **iteration** unless recursion is natural
✔ Tail recursion ≠ optimized in C++


## 4️. Input / Output Optimization

### Why It Matters

Slow I/O = **Rejected solution**

### Best Practice

```cpp
ios::sync_with_stdio(false);
cin.tie(nullptr);
```

✔ Avoid `endl`
✔ Use `\n`
✔ Batch output when possible


## 5️. Bit Manipulation (Google Favorite)

### Why?

→ Faster, elegant, low-level control

### Key Patterns

| Task       | Trick                   |         |
| ---------- | ----------------------- | ------- |
| Check odd  | `n & 1`                 |         |
| Set bit    | `n                      | (1<<i)` |
| Clear bit  | `n & ~(1<<i)`           |         |
| Toggle     | `n ^ (1<<i)`            |         |
| Count bits | `__builtin_popcount(n)` |         |

✔ Used in **optimization**, **masking**, **DP**


## 6️. Core Data Structures (Must-Know)

| DS      | Why Google Uses    |
| ------- | ------------------ |
| Vector  | Cache-friendly     |
| Stack   | Expression parsing |
| Queue   | BFS                |
| Deque   | Sliding window     |
| Heap    | Top-K problems     |
| HashMap | O(1) lookup        |
| Set     | Ordered data       |

✔ Know **trade-offs**, not just usage


## 7️. Algorithms Google Expects

### Searching

* Binary search (all variants)
* Lower/Upper bound

### Sorting

* Quick (average)
* Merge (stable)
* Heap (memory control)

### Graphs

* BFS (shortest path)
* DFS (components)
* Topological sort

### Optimization

* Greedy
* Dynamic Programming
* Divide & Conquer

## 8️. Pattern-Based Thinking (VERY IMPORTANT)

| Pattern                 | Example          |
| ----------------------- | ---------------- |
| Two Pointers            | Sorted arrays    |
| Sliding Window          | Subarrays        |
| Binary Search on Answer | Min/max problems |
| Prefix Sum              | Range queries    |
| Monotonic Stack         | Next greater     |

✔ Google cares about **patterns**, not memorization


## 9️. Mathematical Readiness

✔ Modular arithmetic
✔ Power in log time
✔ GCD / LCM
✔ Overflow handling (`long long`)

```cpp
(a * b) % mod  // avoid overflow
```


## 10. Common Google Mistakes (Avoid)

❌ Brute force
❌ Ignoring constraints
❌ Wrong data type
❌ Overusing recursion
❌ Not explaining logic


## Google Interview Rule

> Correct + Optimal + Clean code + Explanation


## What Google REALLY Tests

✔ Problem-solving ability
✔ Trade-off understanding
✔ Code clarity
✔ Edge case handling
✔ Communication


## Must-Practice Problems

* Two Sum
* Sliding Window Maximum
* Merge Intervals
* Kth Largest Element
* BFS in Matrix
* Subarray Sum = K


## One-Line Summary

> Competitive programming readiness for Google means solving scalable problems using optimal data structures, algorithms, and clean thinking.

---












##### string manipulation
## 🎗 String Manipulation 

## What is a String?
A **string** is a sequence of characters used to store text.

In C++, strings can be handled in **two ways**:

1. **C-style strings (character arrays)**
2. **C++ `string` class (STL)**

### 1. C-style Strings

* Implemented using **character arrays**
* End with a **null character `\0`**

```cpp
char str[20] = "Hello";
```

📌 Stored as: `H e l l o \0`

### 2️. C++ String Class (`<string>`)

* Part of **Standard Template Library (STL)**
* Dynamic, safer, and easier to use

```cpp
#include <string>
string s = "Hello";
```

#### Input & Output of Strings

* Using `cin` and `cout`

```cpp
string s;
cin >> s;      // reads single word
cout << s;
```

* Using `getline()` (recommended)

```cpp
string s;
getline(cin, s);   // reads full line with spaces
```

## Common String Functions (STL)

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

### String Length

```cpp
string s = "Hello";
cout << s.length();   // 5
```


### Concatenation (Joining Strings)

#### Using `+` operator

```cpp
string a = "Hello";
string b = "World";
string c = a + " " + b;
```

#### Using `append()`

```cpp
a.append(b);
```


### Accessing Characters

```cpp
string s = "Hello";
cout << s[0];      // H
cout << s.at(1);   // e
```


### Comparing Strings

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

### Substring

```cpp
string s = "Programming";
string sub = s.substr(0, 7); // Program
```

### Finding a Substring

```cpp
string s = "Hello World";
cout << s.find("World"); // returns index
```

📌 If not found → returns `string::npos`

### Insert & Erase

#### Insert

```cpp
s.insert(5, " C++");
```

#### Erase

```cpp
s.erase(5, 3); //start index, count
```

### Replace

```cpp
s.replace(0, 5, "Hi"); //start index, count, replacment
```

### practical
```cpp
#include <iostream>
#include <string>
using namespace std;

int main(){
// --------- C++ string class (STL)
    string sa = "hello";
    string s;
    cin >> s;  // read single word
    cout << s << endl ;
    cin.ignore();          // clears leftover newline --> this is a add on because cin and getline cant worktogether (hello is stored with /n and getline asume this as the string)
    string t;
    getline(cin,t); //read whole line with space
    cout<< t << endl ;
    // finding length 
    cout << "length of s : " <<  s.length() << endl ;
    cout << "length of t : " << t.length() << endl ;
    // appending
    cout << " append : " <<  s.append(t) << endl ;
    // Accessing Characters
    cout << s[0] << endl ;      // h
    cout << s.at(1) << endl ;   // e
    // compairing
    cout << (s == t) << endl;
    cout << (s.compare(t) == 0) << endl;
    //substring
    cout << s.substr(0, 3) << endl;
    cout << (s.find("World") != string::npos) << endl; // returns index
    // insert , erase , replace
    cout << s.insert(5, " C++") << endl;
    cout << s.erase(5, 3) << endl;
    cout << s.replace(0, 5, "Hi") << endl;
}
```

### C-Style String Functions (`<cstring>`)

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


### Conversion Between String Types

#### string → char array

```cpp
string s = "Hello";
char ch[10];
strcpy(ch, s.c_str());
```

### Traversing a String

#### Using loop

```cpp
for(int i = 0; i < s.length(); i++)
    cout << s[i];
```

#### Using range-based loop

```cpp
for(char c : s)
    cout << c;
```

### Common String Programs (Important)

* Reverse a string
* Check palindrome
* Count vowels/consonants
* Convert to uppercase/lowercase
* Compare two strings
* Find frequency of characters

### Advantages of C++ `string` over C-style strings

| C-style          | C++ string       |
| ---------------- | ---------------- |
| Fixed size       | Dynamic size     |
| Error-prone      | Safe             |
| Manual functions | Built-in methods |

### code 
```cpp
#include <iostream>
#include <cstring>
using namespace std;

int main(){
// --------- C style string function (STL)
    string s = "Hello";
    char ch[10];
    cout << strcpy(ch, s.c_str()) << endl;
    // Traversing a String - Using loop
    for(int i = 0; i < s.length(); i++){
        cout << s[i];
    }
    cout << endl;
    // Traversing a String - range-based loop
    for(char c : s){
        cout << c;
    }
    cout << endl;
    // finding length 
    cout << "length of s : " << strlen(s.c_str()) << endl;
    // concatination
    char ch1[20] = "Hello";
    char ch2[] = "World";
    cout << "concatination : " << strcat(ch1, ch2) << endl;   // ch1 = "HelloWorld"
    // compare
    cout << "compare : " << strcmp(ch1, ch2) << endl;
}
```
---
