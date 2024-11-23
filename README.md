#include <iostream>
using namespace std;
int main() {
    // declare two variables to store the numbers 
    double num1, num2;
    // ask the user to enter the first and second number 
    cout <<"enter the first number:",
    cin >> num1;
    cout <<"enter the second number:",
    cin >> num2;
    // calculate the sum of the two numbers 
    double sum = num1 + num2;
    // display the result 
    cout << "the sum of" << num1 << "and" << num2 << "is" << sum << "." << endl ;
    return 0;
}
