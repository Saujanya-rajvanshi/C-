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
- [boiler plate code](#boile-plate-code)
- [next line](#next-line)
- [output & input](#output-and-input)

##### character set
```cpp
C++ Character Set

Letters:** A–Z, a–z
Digits:** 0–9
Special symbols:** `+  -  *  /  %  =  <  >  !  &  |  ^  ~  ?  :  ;  ,  .  '  "  #  $  @  _  ( )  { }  [ ]`
Whitespace characters:** space, tab (`\t`), newline (`\n`), carriage return (`\r`)
```

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

