# 📘 Java Variables and Data Types

## 🔹 Variable 
A **variable** in Java is a name that stores data (a memory location).  
It’s like a container that holds values.

### 📝 Syntax
```java
datatype variableName = value;
```

👉 **Note:** Variable names should follow **camelCase** convention.  
Example: `collectData`

---

## 🔹 Examples
```java
int age = 20;         // integer variable
double price = 99.99; // decimal variable
```

---

## 🔹 Types of Variables in Java

### 1️⃣ Local Variables  
- Declared inside methods, constructors, or blocks.  

```java
void show() {
    int num = 10; // local variable
    System.out.println(num);
}
```

---

### 2️⃣ Instance Variables (Non-static fields)  
- Declared inside a class but **outside any method**.  
- Each object of the class has its own copy.  

```java
class Student {
    String name; // instance variable
    int age;
}
```

---

### 3️⃣ Static Variables (Class variables)  
- Declared with `static` keyword inside class.  
- Shared among all objects of the class.  

```java
class Student {
    static String school = "DPS"; // static variable
}
```

---

## 🔹 Variable Naming Rules
✅ Must start with a letter, `$`, or `_`  
✅ Cannot use Java **keywords** (like `int`, `class`)  
✅ Case-sensitive (`age` ≠ `Age`)  
✅ Use meaningful names (`marks` is better than `m`)  

---

✨ Now you know the basics of **Java Variables & Data Types** 🚀  
