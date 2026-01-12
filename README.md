# cpp-string-find-first-of
This repository contains a simple C++ program that demonstrates how to use the find_first_of() string function. The program searches for the first occurrence of a specified character in a string and prints its index. It is designed for beginners learning basic string operations in C++.
C++ String Find First Of
📌 Description

This project demonstrates a simple C++ program that uses the find_first_of() function to locate the first occurrence of a character in a string. It helps beginners understand basic string operations in C++.

🧠 Concept Used

C++ string class

find_first_of() function

Basic input/output using cout

💻 Code Example
#include<iostream>
using namespace std;

int main(){
    string s = "how are you";
    cout << s.find_first_of("a") << endl;
    return 0;
}

📝 Explanation

The string "how are you" is stored in a variable.

find_first_of("a") searches for the first occurrence of the character 'a'.

Since 'a' is not present in the string, the function returns string::npos.

🎯 Output
18446744073709551615

