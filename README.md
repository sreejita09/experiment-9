# experiment-9
# Aim 
To study and implement C++Pointer basics
# Apparatus 
VS code 
# Theory 
Theory: 
Pointers are symbolic representations of addresses. They enable programs to simulate call-by-reference as well as to create and manipulate dynamic data structures. Iterating over elements in arrays or other data structures is one of the main use of pointers. 
The address of the variable you’re working with is assigned to the pointer variable that points to the same data type (such as an int or string).

# codes 
~~~
#include <bits/stdc++.h> 
using namespace std;
void geeks()
{
    int var = 5;

    int* ptr; 

    ptr = &var;

    cout<<"Value at ptr = "<<ptr<<"\n";
    cout<<"Value at var = " <<var<<"\n";
    cout<<"Value at *ptr = "<<*ptr<<"\n";

}


int main()
{
    geeks();
    return 0;
} 
~~~
![image](https://github.com/user-attachments/assets/9ee4d0ce-04bf-4b3f-b319-3241bd8c09ca)

~~~
#include <iostream> 
using namespace std; 

int main() 
{
    int* p=new int[7];

    for (int i=0; i<5; i++)
    {
        p[i]=10*(i+1);
    }

    cout<<*p<<"\n"; 
    cout<<*p+1<<"\n";
    cout<<*(p+1)<<"\n";
    cout<<2[p]<<"\n";
    cout<<p[2]<<"\n";
    *p++;

    cout<<*p;

    return 0; 
}
~~~
![image](https://github.com/user-attachments/assets/96f8992f-a6e5-4b63-90ce-1ba7060f42f0)

