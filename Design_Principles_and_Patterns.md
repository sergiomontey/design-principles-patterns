# 📐 Design Principles and Patterns

**Author:** Sergio Montecinos  
**Last Updated:** May 2025  
**License:** MIT  
**Purpose:** Educational content for MonteyCodes YouTube Channel & GitHub Repository

---

## 📘 Introduction

This guide outlines essential **Design Principles** and **Design Patterns** used in modern software development. Whether you're building web, mobile, or desktop applications, mastering these concepts ensures your code is **clean**, **scalable**, and **maintainable**.

---

## 🎯 Design Principles

### 1. **SOLID Principles**
> Five core object-oriented design principles to improve software quality:

- **S**ingle Responsibility Principle  
  _Each class should have one and only one reason to change._

- **O**pen/Closed Principle  
  _Software entities should be open for extension, but closed for modification._

- **L**iskov Substitution Principle  
  _Subtypes must be substitutable for their base types._

- **I**nterface Segregation Principle  
  _Many client-specific interfaces are better than one general-purpose interface._

- **D**ependency Inversion Principle  
  _Depend on abstractions, not on concrete implementations._

---

### 2. **DRY (Don't Repeat Yourself)**
_Eliminate repetition by abstracting repeated code into functions or modules._

### 3. **KISS (Keep It Simple, Stupid)**
_Solutions should be as simple as possible without sacrificing functionality._

### 4. **YAGNI (You Aren’t Gonna Need It)**
_Do not implement something until it is necessary._

### 5. **Separation of Concerns**
_Divide a program into distinct sections, each addressing a separate concern._

---

## 🧱 Design Patterns

### ⚙️ Creational Patterns
Focus on object creation mechanisms.

- **Singleton**: One instance per app (e.g., App config)
- **Factory Method**: Creates objects without specifying class
- **Builder**: Constructs complex objects step-by-step

### 🔁 Structural Patterns
Ease design by identifying relationships.

- **Adapter**: Makes incompatible interfaces work together
- **Composite**: Treat individual objects and compositions uniformly
- **Decorator**: Adds behavior to objects dynamically

### 🔄 Behavioral Patterns
Define how objects interact and communicate.

- **Observer**: One-to-many dependency for event handling
- **Command**: Encapsulates a request as an object
- **Strategy**: Defines a family of interchangeable algorithms

---

## 🧠 Real-World Usage

| Principle/Pattern | Use Case Example                                 |
|-------------------|--------------------------------------------------|
| SRP               | Separate UI logic from data logic in components |
| Factory           | Create multiple types of user cards dynamically |
| Observer          | React state hooks and subscriptions             |
| Decorator         | Add logging/auth features to HTTP requests      |

---

## 🎥 YouTube Integration

📺 *Check out the full walkthrough on my channel:*  
[**MonteyCodes - Design Patterns in Action**](https://www.youtube.com/@MonteyCodes)

---

## 📎 Additional Resources

- [Refactoring Guru](https://refactoring.guru/design-patterns)
- [SourceMaking](https://sourcemaking.com/design_patterns)
- [Design Patterns Book](https://www.oreilly.com/library/view/head-first-design/0596007124/)

---

## 💡 Contribute

Found a pattern I missed or want an example added?  
Feel free to submit a pull request or open an issue!
