# Experiment-4
Aim:To study and implement C++ Bitwise Operators.
Theory:In C++, bitwise operators are used to perform operations directly on the binary representations of integers. These operators are especially useful in low-level programming, such as system programming, embedded systems, and performance-critical code.
The bitwise AND (&) operator compares each bit of two numbers and returns a new number whose bits are set to 1 only if both corresponding bits were 1. The bitwise OR (|) operator sets each bit to 1 if at least one of the corresponding bits is 1. The bitwise XOR (^) operator sets each bit to 1 only if the corresponding bits are different. The bitwise NOT (~) operator inverts all the bits of a number, turning 1s into 0s and vice versa.
Additionally, C++ provides bitwise shift operators: the left shift (<<) moves bits to the left, effectively multiplying the number by powers of two, while the right shift (>>) moves bits to the right, dividing the number by powers of two.
Code:
#include<iostream>
using namespace std;
int main()
{
    int num1,num2;
    cout<<"Enter a number"<<endl;
    cin>>num1;
    cout<<"Enter a number"<<endl;
    cin>>num2;
    int n=num1&num2;
    cout<<"use of AND operator "<<n<<endl;
    int m=num1|num2;
    cout<<"use of OR operator "<<m<<endl;
}
Output:
Enter a number
7
Enter a number
5
use of AND operator 5
use of OR operator 7
Other operators
Code:
#include<iostream>
using namespace std;
int main()
{
    int a,b;
    cout<<"Enter a number"<<endl;
    cin>>a;
    cout<<"Enter a number"<<endl;
    cin>>b;
    int c,d;
    c=a&b;
    d=a|b;
    int a1,a2,a3,a4;
    cout<<"Bitwise And "<< c<<endl;
    cout<<"Bitwise Or "<< d<<endl;
    a1=a^b;
    a2=~a;
    a3=a<<1;
    a4=a>>2;
    cout<<"Bitwise Xor"<<a1<<endl;
    cout<<"Bitwise NOT "<< a2<<endl;
    cout<<"Bitwise leftshift "<< a3<<endl;
    cout<<"Bitwise rightshift "<< a4<<endl;
} 
Output:
Enter a number
3
Enter a number
4
Bitwise And 0
Bitwise Or 7
Bitwise Xor7
Bitwise NOT -4
Bitwise leftshift 6
Bitwise rightshift 0
