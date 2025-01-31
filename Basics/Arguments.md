##### An Argument in Computer Science is the actual input or expression passed or Supplied to a function .
#### Arguments : is an expression value that`s passed to the methods   
>Arguments = Expressions Or Values.

##### Arguments is the defining value that can be added to determine the kind of input that we accept and Don`t have A VALUE.
```cpp
#include<iostream>
using namespace std;
int x, y;
int add(int a,int b);
// function declaration function called add with return type integar
// function argument is a,b and we declared them before as int ,
//so this function will take two arguments each one of them is integar
int main() {
    cout<< "Please Enter First Number : " << endl;
    cin>> x ;
    cout<< "Please Enter Second Number :" << endl;
    cin>> y ;
    cout<<"The Sum Of two Integars is :" << add(x, y) << endl;
//here is x,y passed by value as parameters not arguemnts to calculate the sum of two integars.
//notice the difference between argument and parameters.
//As parameter is variables itself while argument is the supposed entering value
    return 0;
}
int add(int a,int b){
    int c;
    c = a + b;
    return c;
};
// this is function definition that we declared before 
//as it will take two arguments called x,y of type integar and will return integar type variable
//which is called z and it will be the sum of two integar .
```


