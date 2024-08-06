# CDS.exp-3
## Aim:
_**To study and implement Operators in C++**_

## Software:
`Microsoft VSCode`

## Theory:
 Opeartors in C++ are the symbols that are used two perform some mathematocalor logical operations on the variables.
They are classified into 6 types:

**1. Arithmetic Operators:**

+ **Addition** `(+)`: Adds two operands.
+ **Subtraction** `(-)`: Subtracts the second operand from the first.
+ **Multiplication** `(*)`: Multiplies two operands.
+ **Division** `(/)`: Divides the first operand by the second.
+ **Modulus** `(%)`: Returns the remainder of division.

**2. Relational Operators:**

+ **Equal to** `(==)`: Checks if two values are equal.
+ **Not equal to** `(!=)`: Checks if two values are not equal.
+ **Greater than** `(>)`: Checks if the first value is greater than the second.
+ **Less than** `(<)`: Checks if the first value is less than the second.
+ **Greater than or equal to** `(>=)`: Checks if the first value is greater than or equal to the second.
+ **Less than or equal to** `(<=)`: Checks if the first value is less than or equal to the second.

**3. Logical Operators:**

+ **Logical AND** `(&&)`: Returns true if both operands are true.
+ **Logical OR** `(||)`: Returns true if at least one operand is true.
+ **Logical NOT** `(!)`: Reverses the logical state of its operand.

**4. Assignment Operators:**

+ **Simple assignment** `(=)`: Assigns the value on the right to the variable on the left.
+ **Add and assign** `(+=)`: Adds the right operand to the left operand and assigns the result to the left operand.
+ **Subtract and assign** `(-=)`: Subtracts the right operand from the left operand and assigns the result to the left operand.
+ **Multiply and assign** `(*=)`: Multiplies the left operand by the right operand and assigns the result to the left operand.
+ **Divide and assign** `(/=)`: Divides the left operand by the right operand and assigns the result to the left operand.
+ **Modulus and assign** `(%=)`: Takes the modulus using the left and right operands and assigns the result to the left operand.

**5. Bitwise Operators:**

+ **AND** `(&)`: Performs a bitwise AND.
+ **OR** `(|)`: Performs a bitwise OR.
+ **XOR** `(^)`: Performs a bitwise XOR.
+ **NOT** `(~)`: Performs a bitwise NOT.
+ **Left Shift** `(<<)`: Shifts bits to the left.
+ **Right Shift** `(>>)`: Shifts bits to the right.

## Code: 
```
//AKALP SARKAR
//E&TC B2
//EXP 3
//23070123116
#include <iostream>
using namespace std;

struct Point {
    int x;
    int y;
};

int main() {
    // Arithmetic operators
    int a = 10, b = 3;
    cout << "Arithmetic Operators:" << endl;
    cout << "a + b = " << (a + b) << endl;
    cout << "a - b = " << (a - b) << endl;
    cout << "a * b = " << (a * b) << endl;
    cout << "a / b = " << (a / b) << endl;
    cout << "a % b = " << (a % b) << endl;
    
    // Relational operators
    cout << "\nRelational Operators:" << endl;
    cout << "a == b: " << (a == b) << endl;
    cout << "a != b: " << (a != b) << endl;
    cout << "a > b: " << (a > b) << endl;
    cout << "a < b: " << (a < b) << endl;
    cout << "a >= b: " << (a >= b) << endl;
    cout << "a <= b: " << (a <= b) << endl;
    
    // Logical operators
    bool x = true, y = false;
    cout << "\nLogical Operators:" << endl;
    cout << "x && y: " << (x && y) << endl;
    cout << "x || y: " << (x || y) << endl;
    cout << "!x: " << (!x) << endl;

    // Assignment operators
    int c = 10;
    cout << "\nAssignment Operators:" << endl;
    cout << "c = " << c << endl;
    c += 5;
    cout << "c += 5: " << c << endl;
    c -= 3;
    cout << "c -= 3: " << c << endl;
    c *= 2;
    cout << "c *= 2: " << c << endl;
    c /= 2;
    cout << "c /= 2: " << c << endl;
    c %= 3;
    cout << "c %= 3: " << c << endl;
    c &= 2;
    cout << "c &= 2: " << c << endl;
    c |= 1;
    cout << "c |= 1: " << c << endl;
    c ^= 3;
    cout << "c ^= 3: " << c << endl;
    c <<= 1;
    cout << "c <<= 1: " << c << endl;
    c >>= 1;
    cout << "c >>= 1: " << c << endl;

    return 0;
}
```
## Conclusion:
Operators in C++ are essential for performing various operations, from basic arithmetic to complex bitwise manipulation. Understanding these operators and their correct usage is crucial for writing effective and efficient C++ programs.
