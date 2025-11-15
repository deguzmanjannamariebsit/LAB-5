# LAB-5

#include <iostream>
using namespace std;

int main() {
    int grade;
    cout << "Enter grade: ";
    cin >> grade;

    if (grade >= 90)
        cout << "Remark: Excellent";
    else if (grade >= 80)
        cout << "Remark: Very Good";
    else if (grade >= 75)
        cout << "Remark: Satisfactory";
    else
        cout << "Remark: Fail";

    return 0;
}