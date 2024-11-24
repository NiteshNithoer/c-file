#include <iostream>
using namespace std;
int main() {
    double num1, num2, result;
    char operation;

    // ask the user to enter two numbers
    cout << "enter the first number: ";
    cin >> num1;

    cout << "enter the second nummber: ";
    cin >> num2;

    // ask the user for the wanted operation
    cout << "enter the operation (+, -, *, /): ";
    cin >> operation;

   // Controleer en voer de juiste bewerking uit
    switch (operation) {
        case '+':
            result = num1 + num2;
            break;
        case '-':
            result = num1 - num2;
            break;
        case '*':
            result = num1 * num2;
            break;
        case '/':
            if (num2 != 0) {
                result = num1 / num2;
            } else {
                cout << "Fault: dividing by zero is niot allowed." << endl;
                return 1; // end the program with a fault code
            }
            break;
        default:
            cout << "Fault: infinite operations." << endl;
            return 1; // end the program with a fault code
    }

    // show results
    cout << "The result of " << num1 << " " << operation << " " << num2 << " is " << result << "." << endl;

    return 0;
