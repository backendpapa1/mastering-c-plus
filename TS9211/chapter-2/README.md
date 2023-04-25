# mastering-c-plus



```c++
    #include <iostream>

    using namespace std;

    int main (){
        cout << "Hello";
        return 0;
    }
```

## Semicolons and Blocks

**Semicolon** is called an asertion eliminator. it states the end of an instruction or program

```c++
    a = b;
    b = b + 1;
    add(a,b);
```


A **Block** is a logical collection of related statements enclosed in a opening and closing curly braces ```{}```

```c++
    {
    cout << "Hello";
    return 0;
    }
```
An **Identifier** is a mechanism for identify classes, methods and every data involved in c++. it begins with ```A-Z``` or an underscore ```_``` and is followed by any other characters from alphabets to numbers to symbols. identifiers are case sensitive in c++.


A **keyword** are reserved words that can't be used in constants , variables or generally in any identifier. ```page 43 (for list of reserved keywords)```


## Comments

There are two major types of comment:

1. Single line comments
2. Multiline comments

```c++
    /*
     * Hello world multiline commenting
     */
    
    cout << "Hello";// hello world single line commenting    
```

## Data Types

Variables are just memory spaces reserved where values are stored, we can also call it a representation of a memory space.

### Primitive Built in Data Types

1. Boolean ==> bool
2. Character ==> char
3. Integer ==> int
4. Floating point ==> float
5. Double Floating point ==> double
6. Valueless ==> void
7. Wide characters ==> wchar_t

we can modify each of the above primitive values with the following keyword

1. signed
2. unsigned
3. long
4. short


The following are the memory sizes

1. char(1 byte) stores either between ```-127 to 127``` or ```0 to 255```, in its `signed` format -> it stores ```-127 to 127``` and when ```unsigned``` it stores ```0 to 255```.
2. int (4 byte) stores between ```-2.1 billion to 2.1 billion``` when `signed` it ranges between `-2.1B to 2.1B ` and in its `unsigned` format it ranges between `0 to 4.2B`while `short signed`(2 byte) will range between `-32K to 32K`, its `short unsigned`(2 byte) ranges between `0 to 65K`, long(8 byte) is the same as int
3. float is 4 bytes
4. double is 8 bytes
5. long double is 12 byte(4 long bytes + 8 double bytes) = 12;
6. wchar_t is 2 or 4 bytes


<!-- TOC -->
* [mastering-c-plus](#mastering-c-plus)
  * [Semicolons and Blocks](#semicolons-and-blocks)
  * [Comments](#comments)
  * [Data Types](#data-types)
    * [Primitive Built in Data Types](#primitive-built-in-data-types)
<!-- TOC -->