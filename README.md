# C++
C++ language 
### index 
- [basics](#basics)
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
Literals in C++

Literals are fixed constant values used directly in a program.
Types of literals

🌸 Integer literals: 10, -5, 0, 100  - [integer](#integer)

🌸 Floating-point literals: 3.14, 0.5, 2.0 - [Floating-point](#Floating-point)

🌸 Character literals: 'a', 'Z', '9' -[Character](#Character)

🌸 String literals: "Hello", "C++" -[string](#string)

🌸 Boolean literals: true, false -[boolean](#boolean)

🌸 Null pointer literal: nullptr -[null pointer](#null)

👉 Literals represent constant values that do not change during program execution.

---

###### integer 
---
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
## 🔹 Floating-Point Numbers (Notes)

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
## 🔹 Character (Short Notes)

* **Character**: stores a single symbol
* **Type**: `char`
* **Size**: 1 byte
* **Written in**: single quotes `'A'`

**Includes:**

* Letters → `A–Z`, `a–z`
* Digits → `0–9`
* Special symbols → `@ # $ %`
* Whitespace → space, tab, newline

**ASCII-based storage**

* `'A'` = 65, `'a'` = 97, `'0'` = 48

**Escape characters**

* `\n`, `\t`, `\\`, `\'`

**Common functions**

* `isalpha()`, `isdigit()`, `toupper()`, `tolower()`

---

##### string
---
## 🔹 String (Short Notes)

* **String**: collection of characters
* **Type**: `string` (STL)
* **Header**: `<string>`

**Features**

* Dynamic size
* Stores text data
* Uses contiguous memory

**Common Operations**

* Length → `length()` / `size()`
* Access → `at(i)` / `[]`
* Add → `append()`, `+`
* Remove → `erase()`
* Clear → `clear()`

**Input / Output**

* `cin` → single word
* `getline()` → full line

**Important Points**

* Indexing starts from 0
* Strings are mutable
* Safer than C-style strings

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

