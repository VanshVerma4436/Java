# 📘 Java Identifiers, Data Types, Keywords & Literals

---

## 1️⃣ Identifiers in Java
**Definition:**  
Names used to identify variables, methods, classes, or objects.

### ✅ Rules for Valid Identifiers
- Must start with a **letter (A–Z or a–z)**, **underscore (_)**, or **dollar sign ($)**.  
- After the first character, can contain **letters, digits (0–9), underscores (_), or dollar signs ($)**.  
- Case-sensitive → `myVar` and `MyVar` are **different**.  
- Cannot use Java **reserved keywords** (like `int`, `class`, `public`).  
- Cannot contain **spaces or special characters** (`@, #, !, etc.`).  
- No length limit (but recommended **4–15 characters** for readability).  

### 🔹 Examples
- **Valid:** `myVar`, `_counter`, `$value`, `var123`, `EmployeeName`  
- **Invalid:** `123abc` (starts with digit), `my var` (space), `int` (keyword), `var#1` (special char)  

---

## 2️⃣ Data Types in Java
Java is a **strongly typed** language; every variable must have a declared type.

### 🔹 Primitive Data Types

| Type     | Size   | Description                   | Example               | Default Value |
|----------|--------|-------------------------------|-----------------------|---------------|
| `byte`   | 8-bit  | Small integers                | `byte b = 10;`        | 0             |
| `short`  | 16-bit | Medium integers               | `short s = 100;`      | 0             |
| `int`    | 32-bit | Standard integers             | `int i = 5000;`       | 0             |
| `long`   | 64-bit | Large integers                | `long l = 100000L;`   | 0L            |
| `float`  | 32-bit | Floating-point numbers        | `float f = 5.5f;`     | 0.0f          |
| `double` | 64-bit | Double precision float        | `double d = 10.99;`   | 0.0d          |
| `char`   | 16-bit | Single Unicode character      | `char c = 'A';`       | '\u0000'      |
| `boolean`| 1-bit  | True or false values          | `boolean flag = true;`| false         |

### 🔹 Reference Data Types
- **Objects, Strings, Arrays, Classes**  
- The variable holds a **reference (address)** to the actual object.  

---

## 3️⃣ Keywords in Java
**Keywords:** Reserved words with special meanings; cannot be used as identifiers.  

Java has **53 reserved keywords**. Some examples:

`class`, `public`, `static`, `void`, `if`, `else`, `switch`, `case`,  
`try`, `catch`, `finally`, `for`, `while`, `do`, `return`, `new`,  
`this`, `super`, `extends`, `implements`, `interface`, `package`, `import`,  
`instanceof`, `enum`, `abstract`, `synchronized`, `volatile`, `transient`,  
`native`, `final`, `const`, `goto`, `break`, `continue`, `throw`, `throws`,  
`private`, `protected`.  

---

## 4️⃣ Literals in Java
**Literals:** Fixed values directly written in code.

### 🔹 Types of Literals

| Literal Type    | Description               | Examples                  |
|-----------------|---------------------------|---------------------------|
| **Integer**     | Whole numbers             | `100`, `-50`, `0x1A` (hex) |
| **Floating Point** | Decimal numbers         | `3.14`, `2.5e3`           |
| **Character**   | Single Unicode character  | `'A'`, `'\n'`, `'\u0041'` |
| **String**      | Sequence of characters    | `"Hello"`, `"Java123"`    |
| **Boolean**     | True or False values      | `true`, `false`           |
| **Null**        | Represents null reference | `null`                    |

---

## 📝 Summary Table

| Concept     | Description                        | Usage                          | Example                 |
|-------------|------------------------------------|--------------------------------|-------------------------|
| **Identifier** | Names for variables, classes, etc. | Used to identify elements      | `myVar`, `_id`, `count` |
| **Keyword**    | Reserved words with special meaning | Control flow, OOP, syntax      | `class`, `public`       |
| **Literal**    | Fixed value in code               | Assignments, constants         | `100`, `'A'`, `"Hello"` |

---

✅ These notes cover **Java Identifiers, Data Types, Keywords, and Literals** completely and are perfect for **placement or interview preparation**.

# 🎯 Java Placement-Level Interview Questions (Identifiers, Data Types, Keywords & Literals)

---

### 1. What is an identifier in Java?
**Answer:**  
An identifier is the name given to variables, methods, classes, or objects to identify them uniquely in a program.  
It must follow naming rules like starting with a letter, underscore, or dollar sign and cannot be a keyword.

---

### 2. What are the rules for naming identifiers in Java?
**Answer:**  
- Must begin with a **letter (A-Z or a-z)**, **underscore (_)**, or **dollar sign ($)**.  
- Cannot start with a **digit**.  
- Can contain **letters, digits, underscores, or dollar signs** after the first character.  
- Case-sensitive.  
- Cannot be a **reserved keyword**.  

---

### 3. Can a keyword be used as an identifier?
**Answer:**  
No ❌. Java keywords are reserved words and cannot be used as identifiers.  
Example: `int`, `class`, `public` cannot be variable or method names.

---

### 4. What are the primitive data types in Java? Name them.
**Answer:**  
Java has **8 primitive types**:  
`byte`, `short`, `int`, `long`, `float`, `double`, `char`, `boolean`.

---

### 5. What is the difference between primitive and reference data types?
**Answer:**  
- **Primitive Data Types** → store actual values (e.g., `int`, `char`).  
- **Reference Data Types** → store the address/reference of objects in memory (e.g., `String`, Arrays, Classes).  

---

### 6. What is a literal in Java? Give examples.
**Answer:**  
A **literal** is a fixed value directly written in the code.  
Examples:  
- Integer literal → `100`  
- Floating-point literal → `3.14`  
- Character literal → `'A'`  
- String literal → `"Hello"`  
- Boolean literal → `true`, `false`  

---

### 7. What are keywords in Java?
**Answer:**  
Keywords are **predefined reserved words** that have special meaning in Java syntax.  
Examples: `class`, `if`, `else`, `while`, `for`, `try`, `catch`.

---

### 8. Are identifiers case-sensitive in Java?
**Answer:**  
Yes ✅. Java identifiers are case-sensitive.  
Example: `myVar` and `MyVar` are treated as **different identifiers**.

---

### 9. Can variable names contain spaces or special characters?
**Answer:**  
No ❌. Identifiers cannot contain spaces or special characters like `@, #, %`.  
They may only include **letters, digits, underscore (_), and dollar sign ($)**.

---

### 10. What is the default value of an uninitialized int variable?
**Answer:**  
The default value of an uninitialized `int` variable is **0**.

---

### 11. What is the size of different primitive types in Java?
**Answer:**  
- `byte` → 8 bits  
- `short` → 16 bits  
- `int` → 32 bits  
- `long` → 64 bits  
- `float` → 32 bits  
- `double` → 64 bits  
- `char` → 16 bits  
- `boolean` → JVM-dependent (typically 1 bit)  

---

### 12. Can a literal be assigned to a variable of a different data type?
**Answer:**  
Yes ✅, if the literal is compatible.  
Example:  
```java
long l = 100;     // int literal assigned to long
float f = 100;    // int literal assigned to float (widening conversion)
```
### 13. Difference between `==` and `equals()`?
👉 `==` → compares **references (memory addresses)**.  
👉 `equals()` → compares **object content/value**.

---

### 14. What is a string literal?
👉 A sequence of characters enclosed in double quotes.  
Example:
```java
String s = "Java";  // "Java" is a string literal
```
## These Q&A cover the core Java interview concepts on identifiers, data types, keywords, and literals — commonly asked in FAANG-level interviews.
