#include<iostream>
#include<cmath>
using namespace std;

int main(){
    char operation;
    double num1, num2;

    cout << "Enter the first number:";
    cin >> num1;

    cout << "Enter operation(+, -, *, /):";
    cin >> operation;

    cout << "Enter the second number:";
    cin >> num2;

    switch(operation){
        case '+':
            cout << "Result: " << num1 + num2;
            break;

        case '-':
            cout << "Result: " << num1 - num2;
            break;

        case '*':
            cout << "Result: " << num1 * num2;
            break;

        case '/':
            if(num2 != 0){
                cout << "Result: " << num1 / num2;
            }
            else{
                cout << "Error: Division by zero is not allowed.";
            }
            break;

        default:
            cout << "Invalid operation!";
    }

    return 0;
}
