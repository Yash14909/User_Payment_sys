# Java Abstract Class Example: User Payment System

This project demonstrates the use of **abstract classes** and **inheritance** in Java through a user payment system with two types of users:

- **GoldUser**
- **SilverUser**

Each user type provides specific implementations of `pay()` and `receive()` methods, originally declared in an abstract base class `User`.

## 💡 Concepts Covered

- Abstract Classes
- Inheritance
- Method Overriding
- Polymorphism (basic demonstration)
- Clean class structure in Java

## 📂 Files

- `Fourth.java` — Main class with the `main()` method.
- `User` (abstract class) — Declares the `pay()` and `receive()` methods.
- `GoldUser` and `SilverUser` — Concrete subclasses implementing those methods.

## 🚀 How to Run

```bash
javac Fourth.java
java Fourth
