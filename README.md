# Classes-and-objects
# Aim:
To use and implement C++ classes and objects.
# Software used:
Visual studio code.
# Theory
## Classes
Classes are the building blocks of object-oriented programming (OOP). A class is essentially a blueprint for creating objects. It encapsulates data and functions that operate on the data into a single unit. 
### Syntax
```cpp
class MyClass {
public:
    int myNumber;
};
```
```cpp
#include<iostream>
using namespace std;
class student               
{
    public:
    string name;
    int age;
    string branch;          
    float result;
    int year;
    int prn;
};
```
## Objects
An object is an instance of a class. When you define a class, you create a blueprint for objects. Once the class is defined, you can create objects that follow the structure and behavior defined by the class.
### Syntax
```cpp
class MyClass {
public:
    int myNumber;
};

int main() {
    MyClass obj1;  // Create an object of MyClass
    obj1.myNumber = 10;
    obj1.displayNumber();  // Output: Number: 10
    return 0;
}
```cpp
#include<iostream>
using namespace std;
class student               
{
    public:
    string name;
    int age;
    string branch;          
    float result;
    int year;
    int prn;
};
int main()
{
    student s1,s2;

    cout<<"1st student: "<<endl;
    s1.name = "Soham";
    s1.age = 19;
    s1.branch = "ENTC";
    s1.prn = 065;
    s1.result = 7.8;
    s1.year = 2;
    cout<<s1.name<<endl<<s1.age<<endl<<s1.branch<<endl<<s1.prn<<endl<<s1.result<<endl<<s1.year<<endl;
}
```
# Algorithms
### Defining class and objects
1. Start
2. Class Definition:   
   Define a class named student with the following public data members:   
   2.1 string name: To store the student's name.   
   2.2 int age: To store the student's age.   
   2.3 string branch: To store the student's branch of study.   
   2.4 float result: To store the student's result.   
   2.5 int year: To store the student's current academic year.   
   2.6 int prn: To store the student's PRN (Personal Registration Number).   


3. Main Function:   
Declare two objects s1 and s2 of the class student.
4. Input and Output for First Student (s1):   
Assign the following values to the object s1:   
4.1 name = "Soham"   
4.2 age = 19   
4.3 branch = "ENTC"   
4.4 prn = 065   
4.5 result = 7.8   
4.6 year = 2   
4.7 Display the values stored in s1:   
4.8 Print the name, age, branch, prn, result, and year.   

5. Input and Output for Second Student (s2):   
Assign the following values to the object s2:   
5.1 name = "Hussain"   
5.2 age = 19   
5.3 branch = "ENTC"   
5.4 prn = 060   
5.5 result = 8.83   
5.6 year = 2   
5.7 Display the values stored in s2:   
5.8 Print the name, age, branch, prn, result, and year.

6. End

### Defining Method in class
1. Start

2. Class Definition:   
2.1 Define a class named student.   
2.2 Inside the class, define a public method named myMethod():   
2.3 This method outputs the message: "I am studying in 2nd year.".   

3. Main Function:   
4. Declare an object s1 of the class student.   
5. Method Invocation:   
5.1Call the myMethod() function using the object s1.   
6. Output:   
6.1 The program prints the message "I am studying in 2nd year.".   
7. End
