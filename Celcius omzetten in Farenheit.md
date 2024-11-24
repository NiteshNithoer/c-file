#include <iostream>
using namespace std;
int main() {
    double celcius,farenheit;
    // ask the user for a temperature in celcius
    cout << " enter a temperature in celcius:";
    cin >> celcius;
    // convert to farenheit
    farenheit= (celcius* 9.0 / 5.0) + 32.0;
    cout << " It is " << farenheit << " degrees " << endl;
    return 0;
}
