#include <iostream>
using namespace std;

int main() {

    
    int n = 0; 
    cin >> n; 
    for (int i = n; i > 0; --i)
     { cout << i << endl; 
     if (i % 5 == 0) 
     { cout << "Beep" << endl; } }
    return 0;
}

