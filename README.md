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