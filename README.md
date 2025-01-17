#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    int a;
    long long b;
    char c;
    double d, e;

    // Input the values
    cin >> a >> b >> c >> d >> e;

    // Output the values as specified
    cout << a << endl;
    cout << b << endl;
    cout << c << endl;
    cout << fixed << setprecision(3) << d << endl;
    cout << fixed << setprecision(6) << e << endl;

    return 0;
}
