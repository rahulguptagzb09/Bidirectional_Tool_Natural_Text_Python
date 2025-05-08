# Example

Here’s a **list of the most commonly used Python statements** along with their corresponding **natural language representations** in your preferred format:

---

### **Variable Assignment**

- **Code:** `x = 5`
- **Natural Language:** store `5` under the name `x`
- **Code:** `message = "Hello"`
- **Natural Language:** store `"Hello"` under the name `message`

---

### **Control Flow: If, Elif, Else**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    if x > 0:
        print("Positive")
    
    ```
    
- **Natural Language:**if the value stored under the name `x` is greater than `0`, then show on the screen `"Positive"`

---

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    if x > 0:
        print("Positive")
    elif x == 0:
        print("Zero")
    else:
        print("Negative")
    ```
    
- **Natural Language:**if the value stored under the name `x` is greater than `0`, then show `"Positive"` on the screen.otherwise, if the value stored under the name `x` is equal to `0`, then show `"Zero"` on the screen.if none of the above conditions are true, show `"Negative"` on the screen.

---

### **Loops: For Loop**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    for i in range(5):
        print(i)
    
    ```
    
- **Natural Language:**for each value stored under the name `i` in the sequence returned by `range(5)`, show the value of `i` on the screen.

---

### **Loops: While Loop**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    while x < 10:
        x += 1
    
    ```
    
- **Natural Language:**while the value stored under the name `x` is less than `10`, increase the value stored under the name `x` by `1`.

---

### **Function Definition and Call**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    def greet(name):
        print(f"Hello, {name}")
    
    ```
    
- **Natural Language:**
    
    define a function under the name `greet` that takes one parameter stored under the name `name`.
    
    when called, show on the screen `"Hello, "` followed by the value of `name`.
    
- **Code:** `greet("Alice")`
- **Natural Language:** call the function stored under the name `greet` with the value `"Alice"`.

---

### **Return Statement**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    def add(a, b):
        return a + b
    
    ```
    
- **Natural Language:**define a function under the name `add` that takes two parameters stored under the names `a` and `b`.return the result of adding the value of `a` to the value of `b`.

---

### **Exception Handling**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    try:
        x = 1 / y
    except ZeroDivisionError:
        x = 0
    
    ```
    
- **Natural Language:**try to store the result of dividing `1` by the value of `y` under the name `x`.if a `ZeroDivisionError` occurs, store `0` under the name `x`.

---

### **List Operations**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    my_list = [1, 2, 3]
    my_list.append(4)
    
    ```
    
- **Natural Language:**store the list `[1, 2, 3]` under the name `my_list`.append `4` to the list stored under the name `my_list`.

---

### **Dictionary Operations**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    my_dict = {"key": "value"}
    my_dict["new_key"] = "new_value"
    
    ```
    
- **Natural Language:**store the dictionary `{"key": "value"}` under the name `my_dict`.in the dictionary stored under the name `my_dict`, store `"new_value"` under the key `"new_key"`.

---

### **Import Statements**

- **Code:** `import math`
- **Natural Language:** import the module `math`.
- **Code:** `from math import sqrt`
- **Natural Language:** from the module `math`, import the function `sqrt`.

---

### **Class Definition**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    class Person:
        def __init__(self, name):
            self.name = name
    
    ```
    
- **Natural Language:**define a class under the name `Person`.define a function `__init__` inside the class `Person` that stores the value of `name` under `self.name` when the class is instantiated.

---

### **Boolean Operations**

- **Code:** `x = True and False`
- **Natural Language:** store the result of the logical operation `True and False` under the name `x`.
- **Code:** `if not x:`
- **Natural Language:** if the logical negation of the value stored under the name `x` is true, then proceed with the following block.

---

### **List Comprehensions**

- **Code:**
    
    ```python
    python
    KopierenBearbeiten
    squares = [x**2 for x in range(10)]
    
    ```
    
- **Natural Language:**store a list under the name `squares`, where each element is the value of `x` squared for each `x` in the sequence returned by `range(10)`.