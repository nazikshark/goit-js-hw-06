# GoIT JavaScript Homework #06

This repository contains the sixth homework assignment for the JavaScript course. This module focuses on the `this` keyword, Object-Oriented Programming (OOP) principles, and JavaScript Classes.

## 📋 Project Overview
The assignment consists of three tasks designed to practice:
- Context management using the `this` keyword.
- Creating and managing classes.
- Encapsulation using private class fields (the `#` syntax).
- Working with prototype inheritance and class methods.

## 🚀 Tasks Description:

### Task 1: Customer Account Refactoring (`task-1.js`)
Refactoring the methods of a `customer` object to correctly use the `this` keyword. This task ensures proper access to the object's internal properties like `balance`, `discount`, and `orders` within its own methods.

### Task 2: Warehouse Storage Class (`task-2.js`)
Implementation of a `Storage` class that manages an inventory array. 
- **Key Feature**: The `items` array is a **private property** (`#items`), making it inaccessible from outside the class instance.
- **Methods**: `getItems()`, `addItem(newItem)`, and `removeItem(itemToRemove)`.

### Task 3: String Builder Class (`task-3.js`)
Implementation of a `StringBuilder` class for complex string manipulations.
- **Key Feature**: Uses a private `#value` property to store the string state.
- **Methods**: `getValue()`, `padStart(str)`, `padEnd(str)`, and `padBoth(str)`.

## 🛠 Technologies & Concepts Used:
- **JavaScript ES6 Classes**: Class declarations and constructors.
- **Encapsulation**: Using `#` for private properties to protect data.
- **Context (`this`)**: Understanding how `this` refers to the specific instance of a class or object.
- **Array Methods**: Using `filter` or `splice` for data manipulation inside class methods.

## 🔗 Live Page:
[Link to your GitHub Pages here]
