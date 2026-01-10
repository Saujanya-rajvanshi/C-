# C++

### index 
- [basics](#basics)
- [Data handling](#Data-handling)
- [calculator](#calculator)
- [number factors](#number-factor)
- [multiples](#multiples)
- [prime numbers](#prime-number)
- [composite numbers](#composite-numbers)
- [prime factorisation](#prime-factorisation)
- [loss or profit by cp and sp](#loss-or-profit-by-cp-and-sp)
- [validation of triangle](#validation-of-triangle)
- [Arithmetic progression](#Arithmetic-progression)
- [HCF](#HCF)

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



##### boiler plate code
```cpp
#include<iostream>
using namespace std;

int main(){
    cout<< " hello world";
return 0;
}
```

##### next line
```cpp
// new line
cout << endl ;
cout << "\n";
cout << "hello\nworld";
```
##### output and input 
```cpp
//output cout << ;
//input cin >> ;
```
### prime number
```cpp
#include<iostream>
using namespace std;

int main(){
cout<< " hello world";
    // new line
cout << endl ;
cout << "\n";
int n; 
cin >> n;
int i;
for( i = 2;i < 10000000 ;i++ ){
    if(n%i == 0){
        break;
    }
}
if(i == n){
            cout << "prime number";
        }
else{
            cout << "not a prime number";
        }
return 0;
}
```

### composite numbers
```cpp
#include<iostream>
using namespace std;

int main(){
cout<< " hello world";
    // new line
cout << endl ;
cout << "\n";
int n; 
cin >> n;
int i;
for( i = 2;i < 10000000 ;i++ ){
    if(n%i == 0){
        break;
    }
}
if(i == n){
            cout << "not a composite number ";
        }
else{
            cout << "composite number";
        }
return 0;
}
```

### calculator
```cpp
#include<iostream>
using namespace std;

void calculator(){
    cout << "hello its your calculator";
    cout << endl ;
    cout<< "select any operator" << endl << "+ - * / ";
    char opr ;
    cin >> opr ;
    int a, b;
    cout << "enter the first numbers";
    cin >> a;
    cout << "enter the second number";
    cin >> b;
    int answer;
    if ( opr == '+'){
        answer = a+b;
    }
    else if( opr == '-'){
        answer = a-b;
    }
    else if ( opr == '*'){
        answer = a*b;
    }
    else if ( opr == '/'){
        int rem ;
        rem = a % b ;
        cout << " remainer : " << rem ;
        answer = a/b ;
        cout << endl ;
        cout << " quotient : " ;
        
    }
    cout << "your answer  : " << answer;
    cout << endl << endl ;
}

int main(){
    int t;
    cin >> t;
    for(int i=0; i<t; i++){
        calculator();
    }
    return 0;
}
```

### namber factor
```cpp
#include<iostream>
using namespace std;

int main(){
    cout << "hello";
    int n;
    cin >> n;
    for(int i=1;i<=n;i++){
        if(n % i==0){
            cout << i;
        }
    }
    return 0;
}
//never start the loop with zero as it breaks the loop as division by zero is undefined
```
### prime factorisation
```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cin >> n;

    for (int i = 2; i * i <= n; i++) { 
        while (n % i == 0) {
            cout << i << " ";
            n /= i;
        }
    }

    if (n > 1) {
        cout << n;
    }
}

//dont use i<= sqrt(n) it will result in double use i*i <= n
// dont check after half of number in factor question
// if n is prime number n%i  will not be equal to 0 and the thr no. itself will be printed

```

### multiples 
```cpp
#include<iostream>
using namespace std;

int multiples(int n, int k){
    cout << "your multiples are :\n"; 
    for (int i=1;i<=k;i++){
        cout << i*n << " ";
    }
    return 0;
}

int main(){
    cout << "enter the number";
    int n;
    cin >> n;
    cout << "how may nultiples do you want";
    int k;
    cin >> k;

    multiples(n,k);

    return 0;
}
```


### loss or profit by cp and sp 
```cpp
    
#include <iostream>
using namespace std;
int main()
{
    int cp;
    cout<<"enter cost price :";
    cin>>cp;
    int sp;
    cout<<"enter selling price :";
    cin>>sp;
    
    if(cp<sp){
        cout<<"loss";
    }
    else{
        cout<<"profit";
    }

    return 0;
}
```

### validation of triangle 

```cpp
#include <iostream>
using namespace std;
int main()
{
    int a,b,c;
    cout<<"enter first side of the triangle ";
    cin>>a;
    cout<<"enter second side of the triangle ";
    cin>>b;
    cout<<"enter third side of the triangle ";
    cin>>c;
    if((a+b)>c &&(b+c)>a && (c+a)>b){
        cout<<"a valid triangle";
    }
    else {
        cout<<"not a valid triangle";
    }

    

    return 0;
}
```

### Arithmetic progression 

```cpp
#include <iostream>
using namespace std;

int main() {
    int a, d, n;
    cout << "Enter first term (a): ";
    cin >> a;
    cout << "Enter common difference (d): ";
    cin >> d;
    cout << "Enter number of terms (n): ";
    cin >> n;

    cout << "Arithmetic Progression: ";
    for(int i = 0; i < n; i++) {
        cout << a + (i * d) << " ";
    }

    return 0;
}
```


### HCF
```cpp
#include <iostream>
using namespace std;

int main() {
    int n,i;
    cout << "Enter number (n): ";
    cin >> n;
    int hcf;
    for(i=(n/2);i<n;i++){
        if(n%i==0){
            hcf=i;
        }
    }

    cout << "hcf: " << hcf;
    

    return 0;
}
```

```cpp
int maxx(int num1, int num2) {
if (num1 >= num2) return num1;
else return num2;
}
int main() {
int num1, num2;
cin >> num1 >> num2;
int minimum = maxx(num1, num2);
cout << minimu
return 0;
}
```

```cpp
```

