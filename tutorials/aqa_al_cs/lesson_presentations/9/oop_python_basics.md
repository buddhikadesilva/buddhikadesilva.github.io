**Object-Oriented Programming (OOP) in Python** lets you organize code by grouping related data and behaviors into objects. Here’s a super basic tutorial to get you started:

### 1. **Defining a Class**

A **class** is a blueprint for creating objects.

```python
class Dog:
    pass  # Placeholder for now
```

This creates a class named `Dog`[^2].

### 2. **Creating an Object (Instance)**

You make an object from a class by calling the class name:

```python
my_dog = Dog()
print(my_dog)
```

This prints something like `<__main__.Dog object at 0x...>`, showing you have a `Dog` object[^2].

### 3. **Adding Attributes with `__init__`**

To give your objects data (attributes), use the `__init__` method:

```python
class Dog:
    def __init__(self, name, age):
        self.name = name
        self.age = age
```

- `__init__` runs when you create a new object.
- `self` refers to the object being created[^4].

Now, create a dog with a name and age:

```python
my_dog = Dog("Fido", 3)
print(my_dog.name)  # Fido
print(my_dog.age)   # 3
```


### 4. **Adding Methods**

You can add functions (methods) to your class:

```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print("Woof! My name is", self.name)
```

Now call the method:

```python
my_dog = Dog("Buddy")
my_dog.bark()  # Woof! My name is Buddy
```


### 5. **Inheritance (Optional for Beginners)**

A class can inherit from another class:

```python
class Animal:
    def speak(self):
        print("Some sound")

class Cat(Animal):
    pass

my_cat = Cat()
my_cat.speak()  # Some sound
```

Inheritance lets you reuse code from a parent class[^1].

**Key OOP Concepts in Python:**

- **Class:** Blueprint for objects.
- **Object:** Instance of a class.
- **Attribute:** Variable inside an object.
- **Method:** Function inside a class.
- **Inheritance:** One class can inherit from another[^1][^2].

This is the foundation of OOP in Python. You can now start grouping related data and behaviors into classes and create objects from them[^1][^2].

<div style="text-align: center">⁂</div>

[^1]: https://realpython.com/python3-object-oriented-programming/

[^2]: https://www.freecodecamp.org/news/how-to-use-oop-in-python/

[^3]: https://www.youtube.com/watch?v=JeznW_7DlB0

[^4]: https://www.youtube.com/watch?v=Ej_02ICOIgs

[^5]: https://www.ionos.co.uk/digitalguide/websites/web-development/python-object-oriented-programming/

[^6]: https://www.youtube.com/watch?v=PMFd95RgIwE

[^7]: https://www3.ntu.edu.sg/home/ehchua/programming/webprogramming/Python1a_OOP.html

[^8]: https://www.datacamp.com/tutorial/python-oop-tutorial

