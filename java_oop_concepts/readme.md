🧠 Object-Oriented Programming in Java
🚀 Concepts Covered: Encapsulation and Inheritance

This repository contains simple and well-commented Java programs that demonstrate two core Object-Oriented Programming (OOP) principles — Encapsulation and Inheritance.
Each example is short, beginner-friendly, and can be compiled and run independently.


OOP_Encapsulation_Examples/
├── Encapsulation_BasicExample.java
├── Encapsulation_WithValidation.java
├── Encapsulation_MultipleAttributes.java
├── Encapsulation_ConstructorBased.java
└── Encapsulation_GradeSystem.java

OOP_Inheritance_Examples/
├── Inheritance_Single.java
├── Inheritance_OverrideSuper.java
├── Inheritance_Multilevel.java
├── Inheritance_Hierarchical.java
└── Inheritance_InterfaceMultiple.java


🧩 1. Encapsulation
🧠 Concept

Encapsulation is the process of binding data (fields) and methods that operate on that data into a single unit (class).
It is achieved using:

private variables → data hiding

public getters and setters → controlled access

Goal: Protect internal object data and ensure controlled modification.

📘 Encapsulation Program List
| File                                      | Description                                                                                   |
| ----------------------------------------- | --------------------------------------------------------------------------------------------- |
| **Encapsulation_BasicExample.java**       | Demonstrates basic encapsulation with getter and setter methods for a single variable.        |
| **Encapsulation_WithValidation.java**     | Adds data validation logic inside setter methods (e.g., preventing negative balance).         |
| **Encapsulation_MultipleAttributes.java** | Encapsulates multiple private fields (name, id, salary) and provides a unified setter method. |
| **Encapsulation_ConstructorBased.java**   | Shows encapsulation using constructors (read-only object with getters only).                  |
| **Encapsulation_GradeSystem.java**        | Real-life example: stores marks privately and calculates grade internally.                    |


✅ Example Output (Encapsulation_GradeSystem.java)
Grade: B

🧬 2. Inheritance
🧠 Concept

Inheritance allows a class (child) to acquire properties and behavior from another class (parent) using the extends keyword.
This promotes code reusability and models real-world hierarchies.

Goal: Reuse and extend existing code efficiently.

📘 Inheritance Program List
| File                                   | Description                                                                                         |
| -------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **Inheritance_Single.java**            | Basic single-level inheritance (`Dog` inherits from `Animal`).                                      |
| **Inheritance_OverrideSuper.java**     | Demonstrates method overriding and usage of `super` keyword to call parent methods or constructors. |
| **Inheritance_Multilevel.java**        | Shows a multilevel hierarchy (`Vehicle → Car → SportsCar`).                                         |
| **Inheritance_Hierarchical.java**      | Multiple subclasses sharing a single superclass (`Instrument` → `Guitar`, `Piano`).                 |
| **Inheritance_InterfaceMultiple.java** | Demonstrates multiple inheritance via **interfaces** (`Duck` implements `Flyable` and `Swimmable`). |


✅ Example Output (Inheritance_OverrideSuper.java)

Person: Maya
Student roll: 12


