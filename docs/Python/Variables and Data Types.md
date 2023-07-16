## I. Introduction:

In Python, variables are used to store and manipulate data. A variable is essentially a named location in memory where values can be stored and accessed. Variables allow us to assign values, modify them, and retrieve their contents during program execution.

Python supports various data types that determine the kind of data that can be stored in variables. Each data type has specific properties and operations associated with it. Here are some commonly used data types in Python:

**1. Numbers:**

- Python supports numeric data types, including integers (int) and floating-point numbers (float).
- Integers represent whole numbers without a fractional component, such as 5, -3, or 0.
- Floating-point numbers represent numbers with decimal points, such as 3.14, -2.5, or 0.0.

**Example:**


```python
age = 25
price = 19.99
```

**2. Strings:**

- Strings (str) are used to represent textual data, such as names, sentences, or any sequence of characters.
- Strings can be enclosed in single quotes (') or double quotes (").

**Example:**


```python
name = 'Alpha Alimamy'
message = "Hello, world!"
```

**3. Booleans:**

- Booleans (bool) represent truth values and have two possible states: True and False.
- Booleans are typically used in conditionals and logical operations.

**Example:**


```python
is_active = True
is_valid = False
```

**4. Lists:**

- Lists (list) are ordered collections of items enclosed in square brackets ([]).
- Lists can contain elements of different data types and can be modified (mutable).

**Example:**


```python
fruits = ['apple', 'banana', 'orange']
numbers = [1, 2, 3, 4, 5]
```

**5. Tuples:**

- Tuples (tuple) are similar to lists but are enclosed in parentheses (()).
- Tuples are immutable (cannot be modified) once created.

**Example:**


```python
point = (3, 4)
person = ('Alpha Alimamy', 25, 'alpha.alimamy@example.com')
```

**6. Dictionaries:**

- Dictionaries (dict) are key-value pairs enclosed in curly braces ({}).
- Dictionaries allow efficient retrieval and modification of values based on keys.

**Example:**


```python
student = {'name': 'Alpha Alimamy', 'age': 20, 'grade': 'A'}
```

**7. Sets:**

- Sets (set) are unordered collections of unique elements enclosed in curly braces ({}) or using the set() function.
- Sets are useful for performing operations such as union, intersection, and difference.

**Example:**


```python
my_set = {1, 2, 3}
```

### Variable Declaration and Assignment
**- Example: Declaring and Assigning Integer Variables**


```python
age = 25
year = 2023
population = 1000000
quantity = 10_000_000  # Underscores can be used for readability
temperature = -15
```

**Explanation:**

In this example, we declare and assign integer variables. Each variable represents a different value, such as age, year, population, quantity, and temperature.


```python
print(age)
print(year)
print(population)
print(quantity)
print(temperature)
```    
    25
    2023
    1000000
    10000000
    -15
    

**Example: Declaring and Assigning Floating-Point Variables**


```python
pi = 3.14159
temperature = 98.6
rate = 0.05
weight = 72.5
price = 19.99
```

**Explanation:**

Here, we declare and assign floating-point variables. Floating-point numbers are used to represent decimal values.


```python
print(pi)
print(temperature)
print(rate)
print(weight)
print(price)
```

    3.14159
    98.6
    0.05
    72.5
    19.99
    

**Example: Declaring and Assigning String Variables**


```python
name = "Alpha Alimamy"
message = "Hello, world!"
address = '123 Bai Bureh Road'
email = "alpha.alimamy@example.com"
quote = 'Be yourself; everyone else is already taken.'
```

**Explanation:**

String variables are used to store textual data. In these examples, we declare and assign string variables to represent names, messages, addresses, emails, and quotes.

**Example: Declaring and Assigning Boolean Variables**


```python
is_active = True
is_admin = False
has_permission = True
is_valid = False
is_completed = True
```


```python
print(is_active)
print(is_admin)
print(has_permission)
print(is_valid)
print(is_completed)
```

    True
    False
    True
    False
    True
    

**Explanation:**

Boolean variables can have two possible values: True or False. In this case, we declare and assign boolean variables to represent different conditions or states.

**Example: Declaring and Assigning Variables with None**


```python
username = None
result = None
data = None
error = None
response = None
```

**Explanation**:

The value None is used to represent the absence of a value. Here, we declare and assign variables with the value None, indicating that they have not been assigned a specific value yet.


### Python's Built-in Data Types

#### I. Introduction:
Python provides several built-in data types to handle different kinds of data. Let's explore some of the commonly used data types.

**Example: Numbers (Integer and Floating-Point)**


```python
age = 25
price = 19.99
quantity = -5
pi = 3.14159
```

**Explanation:**
In Python, numbers can be represented as integers or floating-point values. In this example, we assign values to variables representing age, price, quantity, and pi.

**Example: Strings**


```python
name = "Rugiatu Salieu"
message = 'Hello, world!'
address = "123 Ferry Junction"
```

**Explanation:**

Strings are used to store textual data. In these examples, we assign string values to variables representing names, messages, and addresses. Strings can be enclosed in single quotes ('') or double quotes ("").

**Example: Booleans**


```python
is_active = True
is_admin = False
has_permission = True
```

**Explanation:**

Booleans represent the truth value of a condition and can have either the value True or False. In this example, we assign boolean values to variables representing different conditions.

**Example: Lists**


```python
fruits = ['apple', 'banana', 'orange']
numbers = [1, 2, 3, 4, 5]
mixed_data = [1, 'two', 3.0, True]
```

**Explanation:**

Lists are ordered collections of items. In these examples, we assign list values to variables representing fruits, numbers, and mixed data. Lists can contain elements of different data types.


**Example: Tuples**


```python
point = (3, 4)
person = ('Alpha Alimamy', 25, 'alpha.kamara@example.com')
```


**Explanation:**

Tuples are similar to lists, but they are immutable (cannot be modified). In this example, we assign tuple values to variables representing a point and a person's information.
Topic: Type Conversion and Casting

## Type Casting:
Python provides functions for converting data between different types. Let's explore type conversion and casting in Python.

**Example: Converting Numbers to Strings**


```python
age = 25
age_str = str(age)
```

**Explanation:**

The str() function is used to convert a number to its string representation. In this example, we convert the age variable (an integer) to a string and assign it to age_str.

**Example: Converting Strings to Numbers**


```python
price_str = '19.99'
price = float(price_str)
```

**Explanation:**

The float() function is used to convert a string representing a floating-point number to its numerical value. In this example, we convert the price_str variable (a string) to a float and assign it to price.


**Example: Converting Numbers to Booleans**


```python
quantity = 10
is_available = bool(quantity)
```

**Explanation:**

The bool() function is used to convert a value to its corresponding boolean representation. In this example, we convert the quantity variable (an integer) to a boolean and assign it to is_available.

**Example: Type Casting**


```python
age = 25
age_str = str(age)
age_int = int(age_str)
```

**Explanation:**

Type casting is the process of explicitly converting a value from one type to another. In this example, we first convert the age variable (an integer) to a string and then convert it back to an integer.


**Example: Automatic Type Conversion**


```python
num1 = 5
num2 = 3.14
result = num1 + num2
```

**Explanation:**

Python automatically performs type conversion when necessary. In this example, the addition operation between an integer and a floating-point number results in an automatic conversion of the integer to a float.
That concludes our discussion on variables, data types, type conversion, and casting. 

### Summary
These are some of the fundamental data types in Python. Understanding data types is essential for performing operations, making decisions, and creating well-structured programs. Python also provides additional built-in data types and allows for the creation of custom data types using classes and objects.

### Further Reading:

Python documentation on built-in types: https://docs.python.org/3/library/stdtypes.html

### Assignment
1. Create a variable called age and assign your age to it. Print the value of the age variable.
2. Create a variable called pi and assign the value of pi (3.14159) to it. Print the value of the pi variable.
3. Create a variable called name and assign your name to it. Print a greeting message using the name variable.
4. Create a list called fruits and populate it with three of your favorite fruits. Print the list of fruits.
5. Create a dictionary called student with keys for "name", "age", and "grade". Assign appropriate values to these keys. Print the dictionary.
6. Create a variable called is_raining and assign a boolean value based on the current weather condition. Print a message indicating whether it is raining or not.
7. Create a tuple called coordinates with latitude and longitude values of a location. Print the coordinates.
8. Create a variable called price and assign a floating-point value to it. Print the price with two decimal places.
9. Create a set called numbers and add the numbers 1, 2, and 3 to it. Print the set of numbers.
10. Perform type conversion on the variables: age, pi, and price. Convert them to strings and print their respective converted values.
11. What are variables ?
12. What is a data type ?
13. How many types of Data types are in Python ?
14. State two differences between a list and a dictionary


```python

```
