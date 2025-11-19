# Interfaces

A simple Java project demonstrating how interfaces work in object-oriented programming with clear examples using geometric shapes.

## Overview

This project defines a `Shape` interface and implements it with two concrete classes:
- `Circle`
- `Rectangle`

The `Main` class creates instances of these shapes and showcases how interfaces enable polymorphism in Java.

## Project Structure

Interfaces/
├── Shape.java
├── Circle.java
├── Rectangle.java
└── Main.java


### **Shape.java**
Defines the interface and the required methods all shapes must implement.

### **Circle.java / Rectangle.java**
Implement the `Shape` interface and provide shape-specific logic.

### **Main.java**
Tests the functionality by creating shapes and calling their methods through the interface.

---

## How to Run


```bash
git clone https://github.com/abaez058/Interfaces.git

cd Interfaces

javac *.java

java Main
