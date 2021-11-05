# Python Basics

## Variables

 Example:
```python
x = 5
y = "John"
print(x)
print(y)
```
>output:<br>
>5 <br>
>john
    
* ### Variable Names
    Legal variable names:
    ```python
    myvar = "John"
    my_var = "John"
    _my_var = "John"
    myVar = "John"
    MYVAR = "John"
    myvar2 = "John"
    ```
    ---
* ### Assign Multiple Values
    - Many values to multiple variables
        ```python
        x, y, z = "Orange", "Banana", "Cherry"
        print(x)
        print(y)
        print(z)
        ```
        Output:
        >Orange<br>
        >Banana<br>
        >Cherry
        ---
    - One Value to Multiple Variables
        ```python
        x = y = z = "Orange"
        print(x)
        print(y)
        print(z)
        ```
        Output:
        >Orange <br>
        >Orange <br>
        >Orange <br>
        ---
    - Unpack a Collection
        ```python
        fruits = ["apple", "banana", "cherry"]
        x, y, z = fruits
        print(x)
        print(y)
        print(z)
        ```
        Output:
        >apple<br>
        >banana<br>
        >cherry
    ---
* ### Output Variables:
    ```python
    x = "Python is "
    y = "awesome"
    z =  x + y
    print(z)
    ```
    Output:
    >Python is awesome


---
## Python Data types
Built-in Data types
| Categories      | Datatype                    |
| --------------- | --------------------------- |
| **Text Type**       | str                         |
| **Numeric Types**   | int, float, complex         |
| **Sequence Types**  | list, tuple, range          |
| **Mapping Types**   | dict                        |
| **Set Types**       | set, Frozen set             |
| **Boolean Type**    | bool                        |
| **Binary Types**    | bytes, bytearray, memoryview|

- Getting the data type
    ```python
    x = "Hello World"
    print(type(x))
    ```
    ><class 'str'>
    ---
    ```python
    x = 20
    print(type(x))
    ```
    ><class 'int'>
    ---
    ```python
    x = 20.5
    print(type(x))
    ```
    ><class 'float'>
    ---
    ```python
    x = 20
    print(type(x))
    ```
    ><class 'int'>
    ---
    ```python
    x = 1j
    print(type(x))
    ```
    ><class 'complex'>
    ---
    ```python
    x = ["apple", "banana", "cherry"]
    print(type(x))
    ```
    ><class 'list'>
    ---
    ```python
    x = ("apple", "banana", "cherry")
    print(type(x))
    ```
    ><class 'tuple'>
    ---
    ```python
    x = range(6)
    print(type(x))
    ```
    ><class 'range'>
    ---
    ```python
    x = {"name" : "John", "age": 36}
    print(type(x))
    ```
    ><class 'dict'>
    ---
    ```python
    x = {"apple", "banana", "cherry"}
    print(type(x))
    ```
    ><class 'set'>
    ---
    ```python
    x = frozenset({"apple", "banana", "cherry"})
    print(type(x))
    ```
    ><class 'frozenset'>
    ---
    ```python
    x = True
    print(type(x))
    ```
    ><class 'bool'>
    ---
    ```python
    x = b"Hello"
    print(type(x))
    ```
    ><class 'bytes'>
    ---
    ```python
    x = bytearray(5)
    print(type(x))
    ```
    ><class 'bytearray'>
    ---
    ```python
    x = memoryview(bytes(5))
    print(type(x))
    ```
    ><class 'memoryview'>
