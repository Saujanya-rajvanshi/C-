# C++
C++ language 
### index 
- [basics](#basics)
- [calculator](#calculator)
- [loss or profit by cp and sp](#loss-or-profit-by-cp-and-sp)
- [validation of triangle](#validation-of-triangle)
- [Arithmetic progression](#Arithmetic-progression)
- [HCF](#HCF)

### basics
```
// boiler plate code
#include<iostream>
using namespace std;

int main(){
    cout<< " hello world";
return 0;
}
```
```
// new line
cout << endl ;
cout << "\n";
cout << "hello\nworld";
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

