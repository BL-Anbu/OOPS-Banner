# 🧩 OOPS Banner Application

## 📌 Project Overview

The **OOPS Banner Application** is a progressive **Java console-based project** designed to demonstrate **Object-Oriented Programming (OOP) principles**, **clean code practices**, and **incremental refactoring**.

The project starts from a **simple console print (UC1)** and evolves step by step into a **scalable, modular banner rendering engine (UC8)** using advanced Java concepts such as **arrays, methods, collections, HashMap, StringBuilder**, and core **OOPS design principles**.

---

## 🎯 Objective

- Print the word **“OOPS”** in a banner format using ASCII art
- Improve the solution incrementally through multiple use cases
- Demonstrate **refactoring, modularity, reusability**, and **clean architecture**
- Apply real-world **OOPS concepts** in a structured manner

---

## 🛠️ Technologies Used

### 🔹 Language
- Java

### 🔹 Core Concepts
- Object-Oriented Programming (OOP) Principles
- Arrays & Loops
- String Handling
- Collections Framework
- HashMap
- StringBuilder

### 🔹 Tools
- Git
- Git Flow
- GitHub  

## 📂 Project Structure

OOPS-Banner-App/

│
├── src/

│ └── OOPSBannerApp.java
│

├── README.md

└── .gitignore


---

## 🚀 Use Case Breakdown

### ✅ UC1: Print Simple OOPS
- Prints **OOPS** as plain text
- **Focus:** Basic Java syntax

---

### ✅ UC2: Banner Using Print Statements
- ASCII art using `System.out.println()`
- Uses `*` and spaces
- **Drawback:** Hardcoded and repetitive

---

### ✅ UC3: Banner Using `String.join()`
- Replaces `+` operator with `String.join()`
- Improves readability and memory efficiency

---

### ✅ UC4: Banner Using String Array & Loop
- Stores banner lines in a `String[]`
- Uses loop for rendering
- Improves modularity

---

### ✅ UC5: Inline Array Initialization
- Combines declaration and initialization
- Uses `String.join()` inline
- Reduces verbosity

---

### ✅ UC6: Refactor Banner Logic into Methods
- Separate methods for characters **O**, **P**, **S**
- Applies **DRY Principle**
- Improves reusability and maintainability

---

### ✅ UC7: Store Character Pattern in a Class
- Introduces `CharacterPatternMap` class
- Encapsulates character → pattern mapping
- Demonstrates **OOPS principles**

---