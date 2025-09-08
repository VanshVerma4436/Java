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
