# Lab-Exercise-1-Array-Index-and-Bounds
#include <iostream>
using namespace std;

int main() {
    int numbers[5] = {10, 20, 30, 40, 50};
    int index;

    cout << "Enter an index (0-4): ";
    cin >> index;

    // Check for valid index
    if (index >= 0 && index < 5) {
        cout << "Value at index " << index << ": " << numbers[index] << endl;
    } else {
        cout << "Error: Index out of bounds!" << endl;
    }

    return 0;
}

# Lab Exercise 2 – Array Initialization
#include <iostream>
using namespace std;

int main() {
    
    double sales[] = {12.25, 32.50, 16.90, 23.00, 45.68};

    cout << "Sales values: ";
    for (int i = 0; i < 5; i++) {
        cout << sales[i] << " ";
    }
    cout << endl;

    double total = 0;
    for (int i = 0; i < 5; i++) {
        total += sales[i];
    }
    double average = total / 5;
    cout << "Average sales: " << average << endl;

    return 0;
}

#include <iostream>
using namespace std;

int main() {
   
    double sales[5] = {12.25, 32.50, 16.90};

    cout << "Sales values: ";
    for (int i = 0; i < 5; i++) {
        cout << sales[i] << " ";
    }
    cout << endl;

    return 0;
}

#  Lab 3 – Partial Initialization
#include <iostream>
using namespace std;

int main() {
    int list1[10] = {0};
    int list2[10] = {8, 5, 12};
    int list3[3]  = {5, 6, 3};
    int list4[25] = {4, 7};

    cout << "list1: ";
    for (int i = 0; i < 10; i++)
        cout << list1[i] << " ";
    cout << endl;

    cout << "list2: ";
    for (int i = 0; i < 10; i++)
        cout << list2[i] << " ";
    cout << endl;

    cout << "list3: ";
    for (int i = 0; i < 3; i++)
        cout << list3[i] << " ";
    cout << endl;

    cout << "list4: ";
    for (int i = 0; i < 25; i++)
        cout << list4[i] << " ";
    cout << endl;

    return 0;
}
