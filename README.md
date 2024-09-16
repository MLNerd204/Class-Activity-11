#include <iostream>
using namespace std;

int main() {
    // Declare variables to store user input
    int value1, value2, largerValue;

    // Prompt user to enter two values
    cout << "Enter the first value: ";
    cin >> value1;
    cout << "Enter the second value: ";
    cin >> value2;

    // Determine the larger value using an if statement
    if (value1 > value2) {
        largerValue = value1;
    } else {
        largerValue = value2;
    }

    // Print the larger value
    cout << "The larger value is: " << largerValue << endl;

    return 0;
}





We first read two integer values from the user. We then use an if statement to compare the two values and store the larger 
one in the largerValue variable. We then output the largest value that is stored in the programming.
