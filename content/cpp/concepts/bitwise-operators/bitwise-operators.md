---
Title: 'Bitwise Operators'
Description: 'C++ supports different types of arithmetic operators that can perform common mathematical operations: - + addition - - subtraction - * multiplication - / division - % modulo (yields the remainder) cpp'
Subjects:
  - 'Computer Science'
  - 'Game Development'
Tags:
  - 'Operators'
  - 'Binary'
  - 'Bitwise-Operators'
  - 'Logical'
CatalogContent:
  - 'learn-c-plus-plus'
  - 'paths/computer-science'
---

## Bitwise Operators

C++ supports different types of bitwise operators that can perform operations on integers on bit level, types of Bitwise Operators supported in C++ are:

- `&` Bitwise AND
- `|` Bitwise OR
- `<<` Bitwise Left Shift
- `>>` Bitwise Right Shift
- `~` Bitwise Complement 
- `^` Bitwise XOR

#### 1. `&` Bitwise AND:

The Bitwise AND operator returns 1 if both the bits are 1 else, it returns 0.

For example:
```pseudo
4 = 100 (Binary)
5 = 101 (Binary)

    100
    101
    ___
    100, which is equal to 4 in Decimal System
```

We can verify that by running the following code:

```codebyte/cpp
# include<iostream>

int main() {
    std::cout << (4 & 5) << std::endl;
    
    return 0;
}
```