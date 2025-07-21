
# 🧠 Object-Oriented Programming (OOP) Report

## 📌 Introduction
Object-Oriented Programming (OOP) is a programming paradigm based on the concept of "objects", which can contain data (attributes) and code (methods). It aims to model real-world entities and their interactions, making code more reusable, maintainable, and scalable.

---

## 🧱 The Four Pillars of OOP

### 1. 🔒 Encapsulation
- Encapsulation means bundling data and methods that operate on that data within one unit (class).
- It restricts direct access to some of the object's components, improving data security and reducing complexity.

### 2. 🧼 Abstraction
- Abstraction hides internal implementation details and shows only the necessary features.
- It helps in focusing on what an object does instead of how it does it.

### 3. 🧬 Inheritance
- Inheritance allows one class (child) to acquire properties and behaviors of another class (parent).
- It promotes code reuse and logical hierarchy.

### 4. 🌀 Polymorphism
- Polymorphism means "many forms". It allows methods to do different things based on the object that invokes them.
- Example: `start()` method in a `Car` vs. `Truck`.

---

## 🔍 Key Concepts

| Concept        | Description |
|----------------|-------------|
| **Class**      | Blueprint for creating objects (e.g., Vehicle) |
| **Object**     | Instance of a class (e.g., myCar) |
| **Constructor**| Initializes a new object |
| **this**       | Refers to the current object |
| **Static**     | Belongs to the class rather than any object |
| **Interface**  | Defines a contract that classes must follow |
| **Abstract Class** | Contains both defined and undefined methods |
| **Overloading** | Same method name, different parameters |
| **Overriding**  | Redefining a parent method in child class |

---
![Object-Oriented Programming Concepts](images/Object-Oriented-Programming-Concepts%20(1).jpg)

 
## 🎮 Game-Themed Java Example

```java
// Base class
class Character {
    void attack() {
        System.out.println("The character attacks!");
    }
}

// Subclass 1
class Warrior extends Character {
    @Override
    void attack() {
        System.out.println("Warrior swings a sword!");
    }
}

// Subclass 2
class Mage extends Character {
    @Override
    void attack() {
        System.out.println("Mage casts a fireball!");
    }
}

// Subclass 3
class Archer extends Character {
    @Override
    void attack() {
        System.out.println("Archer shoots an arrow!");
    }
}
```

🧠 This example shows **polymorphism**—each character attacks in their own unique way, even though the method name is the same.
It also demonstrates **inheritance**, as all characters share the base structure from the `Character` class.
---

## ✅ Benefits of OOP
- Encourages **modular programming**
- Enables **code reuse** through inheritance
- Promotes **cleaner and more maintainable code**
- Supports **real-world modeling**

---

## 🏁 Conclusion
OOP is a powerful paradigm that helps developers write organized, scalable, and maintainable code by modeling software after real-world entities. Understanding its principles is essential for building modern applications in languages like Java, Python, C++, and others.


---

## 📚 References

1. GeeksforGeeks - [Object-Oriented Programming (OOP) Concepts](https://www.geeksforgeeks.org/java/object-oriented-programming-oops-concept-in-java/)
2. W3Schools - [Java OOP](https://www.w3schools.com/java/java_oop.asp)
3. Medium - [A Quick Recap of OOP in Java](https://medium.com/quick-recap-of-engineering-courses/a-quick-recap-of-object-oriented-programming-oop-in-java-ae2ff8e07c36)
4. YouTube - [The Four Principles of Object Oriented Programming](https://www.youtube.com/watch?v=YpYLXq4htKY)


[def]: images/Object-Oriented-Programming-Concepts%20(1).jpg