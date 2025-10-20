# LeslieMBrock-Correction
Week 6 Discussion Board
// This program demonstrates enumeration types in C++
// It contains two syntax errors originally and shows how to assign values to enum members
// This keeps the code neat, tidy, and readable—especially for selecting a medium shirt size

#include <iostream>
using namespace std;

enum sizes { small = 1, medium = 2, large = 3, extra_large = 4 };

int main() {
    sizes shirt_size;
    shirt_size = medium;

    if (shirt_size == medium) {
        cout << "The size of the shirt is medium." << endl;
    } else {
        cout << "The size of the shirt is not medium." << endl;
    }

    return 0;
}
