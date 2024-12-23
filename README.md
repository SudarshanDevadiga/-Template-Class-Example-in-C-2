# Template Class Example 2 in C++

A demonstration of class templates in C++ with multiple type parameters, showing how a single class definition can work with different data types.

## Description

This program implements a template class `Test` that can store and display two values of different data types. It showcases the flexibility of class templates in C++ by allowing multiple type parameters.

### Key Features
- Class template with multiple type parameters
- Template parameter flexibility
- Constructor initialization
- Display functionality
- Type-safe operations

## Class Template Structure

```cpp
template <class T1, class T2>
class Test
{
    T1 a;
    T2 b;
public:
    Test(T1 x, T2 y);
    void show();
};
