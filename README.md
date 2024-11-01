#include <iostream> 
using namespace std;

int main() {
    
    string name; 
    double num1, num2; 
   
    cin >> name;

    cout << "Hello, " << name << "! Please enter two numbers: ";
    cin >> num1 >> num2;

    cout << "\nResults:\n"; 
    cout << "Addition: " << num1 + num2 + num3 << endl; 
    cout << "Subtraction: " << num1 - num2 - num3 << endl; 
    cout << "Multiplication: " << num1 * num2 * num3 << endl; 

    if (num2 != 0) {
        cout << "Division: " << num1 / num2 << endl; 
    } else {
        cout << "Division: Cannot divide by zero!" << endl; 
    }

    return 0; 
}
