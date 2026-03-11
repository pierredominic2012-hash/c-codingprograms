# Making a calculator using C++ Programming
 #### You can do whatever you want with C++ Programming and one of them is creating a calculator

## Open a coding app
* Make sure that you choose C++ Programming coding app
## Start coding
 * Copy and paste this into the lines:
` #include <iostream>
using namespace std;

int main() {
    float num1, num2;
    char op;
   
    cout<<"Enter your number 1: " ;
    cin>>num1;
    cout<<" Enter operator (+,-,*,/): ";
    cin>>op;
    cout<<"Enter your number 2: ";
    cin>>num2;
   
    if (op == '+')
        cout<<"Result: " << num1 + num2;
    else if (op == '-')
        cout<<"Result: " << num1 - num2;
    else if (op == '*')
        cout<<"Result: " << num1 * num2;
    else if (op == '/')
        cout<<"Result: " << num1 / num2;
    else
        cout<<"Invalid result";
       
return 0;
} `
