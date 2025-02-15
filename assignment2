#include <iostream>
#include <cstring>

using namespace std;

bool isValidPhoneNumber(char phoneNumber[]) {
    // Check if the number has exactly 10 digits
    if (strlen(phoneNumber) != 10) {
        return false;
    }

    // Check if the number starts with 7, 8, 9, or 6
    if (phoneNumber[0] != '7' && phoneNumber[0] != '8' && phoneNumber[0] != '9' && phoneNumber[0] != '6') {
        return false;
    }

    // Check if all characters are digits
    for (int i = 0; i < 10; i++) {
        if (!isdigit(phoneNumber[i])) {
            return false;
        }
    }

    return true;
}

int main() {
    char phoneNumber[11]; // Array to store phone number with 10 digits + null terminator

    cout << "Enter phone number: ";
    cin >> phoneNumber;

    if (isValidPhoneNumber(phoneNumber)) {
        cout << "The phone number is valid." << endl;
    } else {
        cout << "The phone number is invalid." << endl;
    }

    return 0;
}