# 🧑‍🏫 Java Full Course - Introduction

Welcome to the **Java Full Course** on *JayantCodeCraft*!  
This course is 100% free and beginner-friendly, designed to take you from **zero to advanced** level.

---

## 📌 What is Java?

- Java is a **high-level**, **object-oriented**, and **platform-independent** programming language.
- Developed by **Sun Microsystems** in 1995 (now owned by **Oracle**).
- Famous for its principle: **Write Once, Run Anywhere (WORA)**.

---

## 🌟 Why Learn Java?

✅ Popular language in software development  
✅ Strong community and open-source libraries  
✅ Used in Android apps, enterprise software, web apps, and more  
✅ Best for interviews  
✅ Platform-independent – runs on Windows, Mac, Linux  
✅ Base for learning Spring Boot, Hibernate, and Microservices

---

## 👨‍🎓 Who Should Learn Java?

- College students (CS/IT/BCA/MCA)
- Freshers preparing for jobs
- Backend/API developers
- Complete beginners in programming
- Working professionals looking to upskill

---

## 📚 Course Roadmap

| Module | Topics |
|--------|--------|
| ✅ Module 1 | Java Basics (Variables, Data Types, Operators) |
| ✅ Module 2 | Control Statements (if, switch, loops) |
| ✅ Module 3 | Functions & Methods |
| ✅ Module 4 | Object-Oriented Programming (OOPs) |
| ✅ Module 5 | Arrays and Strings |
| ✅ Module 6 | Exception Handling |
| ✅ Module 7 | Java Collections Framework |
| ✅ Module 8 | File Handling |
| ✅ Module 9 | Java 8 Features (Lambda, Stream API) |
| ✅ Module 10 | Multithreading & Concurrency |
| ✅ Module 11 | JDBC – Java Database Connectivity |
| ✅ Final Project | Mini Project using Core Java |

---

## 🛠 Tools Required

| Tool | Purpose |
|------|---------|
| JDK (Java Development Kit) | Compiling and running Java programs |
| IDE (Eclipse / IntelliJ IDEA) | Writing and debugging code |
| Terminal or Command Prompt | Running `.java` files |
| Git & GitHub (Optional) | Version control and sharing code |

---

## 📦 Course Format

- 📘 Concept Explanation
- 💻 Live Coding Demonstration
- ❓ Real Interview Questions
- 🧠 MCQs & Assignments
- 🧪 Mini Projects

---

## 🚀 How to Make the Most of this Course?

✅ Watch each video completely  
✅ Write code along with me  
✅ Take notes in your own words  
✅ Push your code to GitHub daily  
✅ Ask doubts in the comments  
✅ Share with friends who want to learn Java

---

# ☕ Java Setup - Install JDK + Eclipse + Hello World Program

Welcome to the second part of the *Java Full Course* by JayantCodeCraft!  
In this lesson, we will:

- Understand the key components of Java (JDK, JRE, JVM)
- Install JDK
- Set up Eclipse (free IDE)
- Write and run your first Java program – "Hello World!"

---

## 📦 What is JDK (Java Development Kit)?

- JDK stands for *Java Development Kit*.
- It contains everything you need to *develop* Java applications.
- It includes:
  - *JRE (Java Runtime Environment)* – To run Java programs
  - **Compiler (javac)** – To compile .java code into .class bytecode
  - *Tools* – Debugger, JavaDoc, etc.

👉 Without JDK, you cannot *compile and run* Java code.

---

### 🔹 JVM (Java Virtual Machine)
- JVM is like a *virtual computer inside your computer* that runs Java programs.
- It reads .class files (compiled Java files) and executes them.
- It provides *platform independence*, meaning your code can run on any OS.

🧠 *Real-life example*: Think of JVM as a DVD player. You can play the same DVD (Java program) on any DVD player (JVM), regardless of the brand (Windows/Linux/Mac).

---

### 🔹 JRE (Java Runtime Environment)
- JRE contains JVM + libraries + other files needed to run Java applications.
- it's the runtime platform that allows Java programs to function on a specific operating system. 

🧠 *Real-life example*: JRE is like a music app where you can only listen to songs (run code), but you can't create or edit them (write code).

---

## 🔍 Difference Between JDK, JRE, and JVM

| Component | Description |
|----------|-------------|
| *JVM*  | Java Virtual Machine – runs .class (bytecode) files |
| *JRE*  | Java Runtime Environment – contains JVM + libraries to run Java apps |
| *JDK*  | Java Development Kit – contains JRE + development tools (compiler, debugger) |

---

## 🛠 Installing Java JDK

### Step 1: Download JDK

- Visit the official Oracle JDK website: [https://www.oracle.com/java/technologies/javase-downloads.html](https://www.oracle.com/java/technologies/javase-downloads.html)
- Choose the latest *LTS (Long-Term Support)* version (like Java 17 or Java 21)
- Download the installer according to your OS (Windows / Mac / Linux)

### Step 2: Install JDK

- Follow on-screen instructions to install
- After installation, go to terminal and check:

```bash
java -version
javac -version
```
✅ If both commands give version output, Java is successfully installed!

----


## ⚙ Step 2: Set Environment Variable (Windows only)

If javac not found:

1. Copy your JDK bin path (e.g., C:\Program Files\Java\jdk-21\bin)
2. Go to:
   - This PC → Right-click → Properties → Advanced system settings → Environment Variables
3. Under *System Variables*, find Path → Edit → New → Paste the path
4. ✅ Done! Now reopen Command Prompt and try javac -version

---

## 💻 Step 3: Download & Setup Eclipse IDE

1. Go to [https://www.eclipse.org/downloads/](https://www.eclipse.org/downloads/)
2. Download *Eclipse IDE for Java Developers* or Download *Eclipse IDE for Enterprise Edition*(If you want to do web development in future)
3. Go for Enterprise Edition: [https://www.eclipse.org/downloads/packages/release/2024-06/r/eclipse-ide-enterprise-java-and-web-developers](https://www.eclipse.org/downloads/packages/release/2024-06/r/eclipse-ide-enterprise-java-and-web-developers)
4. Install and launch it.
5. Select a *workspace folder* (where your Java projects will be saved)
6. Eclipse opens with a welcome screen. Close it.

---

## 🧪 Step 4: Create First Java Program - "Hello World"

### 📝 Steps:

1. Open Eclipse → File → New → Java Project  
   - Project Name: FirstJavaProject

2. Right-click on src → New → Package  
   - Package name: com.hello

3. Right-click on the package → New → Class  
   - Class name: HelloWorld  
   - Check ✅ "public static void main"

4. Inside the class, Eclipse will generate a main method. Type:

```java
package com.hello;

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
```
5. ✅ Right-click inside the editor → Run As → Java Application

---

### 🖥 Output:
```
Hello, world!
```
---

### 📌 Key Points in Code

| Keyword            | Meaning                                      |
|--------------------|---------------------------------------------|
| `public`           | Accessible from anywhere                    |
| `class`            | Blueprint for creating objects              |
| `static`           | Can run without creating object             |
| `void`             | No return value                             |
| `main`             | Entry point of Java program                 |
| `String[] args`    | Command-line argument array                 |
| `System.out.println()` | Prints message to console               |

---

### 🤔 Real-Life Analogy for main() Method
- Think of Java program like a Book.

- main() method is the starting page scene where the story begins.

- Without a single page we cannot say this book is complete, unless it is a Cover only

- Without main(), JVM doesn’t know from where to start.

### 🎯 What You Learned
- ✅ JDK, JRE, JVM - definitions and differences
- ✅ Installed JDK and Eclipse
- ✅ Wrote and ran your first Java program
- ✅ Understood structure of Java code

---

# 🔤 Java Programming Basics

Welcome to *Module 1: Java Basics* of the Java Full Course!  
In this module, we’ll cover the *fundamental building blocks* of Java: *keywords, **identifiers, **variables, and **data types*.

---

## 📌 Keywords in Java

- Keywords are *reserved words* used by Java to define the *syntax and structure* of the language.
- You *cannot* use them as variable, class, or method names.

### ✅ Examples of Keywords:

| Category | Examples |
|---------|----------|
| Access Modifiers | public, private, protected |
| Data Types | int, float, double, char, boolean |
| Control Flow | if, else, switch, case, for, while, do |
| Class-related | class, interface, extends, implements, new |
| Exception Handling | try, catch, finally, throw, throws |
| Others | static, void, return, this, super, import, package, final |

> 🧠 Tip: Java has *50 reserved keywords*. They are case-sensitive.

---

## 🧾 Identifiers in Java

- Identifiers are the *names* you give to variables, methods, classes, etc.
- Rules for writing identifiers:
  - Must start with a letter (A–Z or a–z), `_`, or $
  - Cannot start with a digit
  - Cannot use Java keywords
  - Case-sensitive (name ≠ Name)
  - No spaces or special characters allowed

### ✅ Valid Identifiers:
```java
firstName
_totalMarks
$salary
myVariable123
```

### ❌ Invalid Identifiers:
```java
1stValue        // Starts with digit
class           // Keyword
total marks     // Contains space
@value          // Special character
```

---

## 🧮 Variables in Java
- Variables are containers used to store data.
- Every variable has:
    - Type (what kind of data)
    - Name (identifier)
    - Value

#### ✅ Syntax:
```java
dataType variableName = value;
```
#### ✅ Example:
```java
int age = 25;
String name = "Jayant";
boolean isJavaFun = true;
```

#### 🧠 Real Life Analogy:
- Variable is like a labeled jar that holds something.
    - int age = 25; → A jar labeled "age" with number 25 inside.

---

## 🎲 Data Types in Java
Java is a *statically typed* language → data type must be declared before using a variable.

`*Note :` A statically typed language is a programming language where the type of a variable is checked at compile time, before the code is executed. This means the compiler verifies that the operations performed on variables are valid based on their declared types.

### 📚 Types of Data Types:
| Category      | Data Types                                      |
|--------------|------------------------------------------------|
| **Primitive** | - `byte`<br>- `short`<br>- `int`<br>- `long`<br>- `float`<br>- `double`<br>- `char`<br>- `boolean` |
| **Non-Primitive** | - `String`<br>- `Arrays`<br>- `Class`<br>- `Interface` |


### 🔢 Primitive Data Types
- Built-in/basic data types in Java.
- There are *8 primitive types*.
- They store *simple values* directly.
- Memory-efficient and *fast*.
- *Not objects*.
- Stored in *stack memory*.

| Type      | Size     | Example             | Range | Description |
|-----------|----------|---------------------|-------|-------------|
| `byte`    | 1 byte   | `byte a = 100;`     | -128 to 127 | Small integers |
| `short`   | 2 bytes  | `short s = 5000;`   | -32,768 to 32,767 | Larger than byte |
| `int`     | 4 bytes  | `int x = 100000;`   | -2³¹ to 2³¹-1<br>(-2,147,483,648 to 2,147,483,647) | Common integer type |
| `long`    | 8 bytes  | `long l = 123456789L;` | -2⁶³ to 2⁶³-1<br>(-9,223,372,036,854,775,808 to 9,223,372,036,854,775,807) | Very large numbers |
| `float`   | 4 bytes  | `float f = 10.5f;`  | ±1.4E-45 to ±3.4E+38<br>(6-7 decimal digits precision) | Single-precision floating point |
| `double`  | 8 bytes  | `double d = 20.99;` | ±4.9E-324 to ±1.7E+308<br>(15 decimal digits precision) | Double-precision floating point |
| `char`    | 2 bytes  | `char ch = 'A';`    | 0 to 65,535 (unsigned) | Single Unicode character |
| `boolean` | 1 bit    | `boolean flag = true;` | true/false | Logical true/false values |

> Unicode is a universal character encoding standard that assigns a unique number (code point) to every character, symbol, and script across different languages. Java uses Unicode to represent text, allowing it to handle multiple languages and special characters consistently.

```java
 public class UnicodeLetters {
    public static void main(String[] args) {

        char latinA = 'A';          // Latin
        char greekAlpha = 'α';      // Greek
        char hindiKa = 'क';    // Hindi

        char euro = '\u20AC';   // € (Euro symbol)
        char sigma = '\u03A3';  // Σ (Greek Sigma)
        String emoji = "\uD83D\uDE0E"; // 😎 (smiling face with sunglasses)

        System.out.println(Character.isLetter(latinA));       // true
        System.out.println(Character.isLetter(greekAlpha));   // true
        System.out.println(Character.isLetter(hindiKa)); // true
        System.out.println(Character.isLetter(chineseChar));  // true
        System.out.println(Character.isLetter('1'));          // false (digit)

        System.out.println(euro);   // Output: €
        System.out.println(sigma);  // Output: Σ
        System.out.println(emoji);  // Output: 😎
    }
}
```

### 🔤 Non-Primitive Data Type
- Not built-in: *created using classes and interfaces*.
- Store *multiple values* or *complex data*.
- *Objects or references*.
- Stored in *heap memory, variable holds **reference (address)*.
- Examples include String, Array, Class, Interface, Enum, List, etc.


##### - String: Sequence of characters

```java
String name = "Jayant";
```

##### - Arrays: Collection of similar types

```java
int[] numbers = {1, 2, 3};
```

---

## 🔤 What is var type in Java?
#### ✅ Definition:
- Introduced in Java 10.
- var is a reserved type name, not a keyword
- The compiler automatically infers the data type from the assigned value.
- Using var as a class or interface name is not permitted. 

```java
var name = "Jayant";    // Inferred as String
var age = 25;           // Inferred as int
var salary = 10.5f;     // Inferred as float
```
> 🧠 var helps reduce boilerplate code but doesn't make Java dynamically typed.

##### ❗Rules:
- You must initialize the variable at the time of declaration.
- Cannot assign null without explicit casting.
- Cannot use var for class fields, method parameters, or return types (only local variables).

##### 🧾 Example:
```java
var x = 50;         // Compiler sees this as int
var message = "Hi"; // Compiler sees this as String
```


### 🔍 Key Differences Between Primitive and Non-Primitive Types

| Feature               | Primitive Data Type               | Non-Primitive Data Type               |
|-----------------------|-----------------------------------|---------------------------------------|
| **Definition**        | Basic built-in data types         | Custom/reference types (classes)      |
| **Size**             | Fixed (e.g., int=4 bytes)        | Variable (depends on object)          |
| **Memory**           | Stored in stack memory           | Object in heap, reference in stack    |
| **Objects**          | Not objects                      | Are objects                           |
| **Methods**          | Cannot call methods              | Have built-in methods                 |
| **Example**          | `int`, `char`, `boolean`         | `String`, `Array`, `Class`, `List`    |
| **Default Value**    | Type-dependent (0, false, etc.)  | `null`                                |

---

## 📌 Type Casting
- Typecasting, also known as type conversion, is the process of changing a variable's data type into another.

It is Two types: 

### ✅ Implicit Casting (Widening)
- Implicit Type Conversion is commonly referred to as 'Automatic Type Conversion.' It occurs automatically within the compiler without requiring external intervention from the user.
- It refers to the automatic conversion of a value from a smaller data type to a larger.
```java
int x = 10;
double y = x;  // int → double automatically
```

### ✅ Explicit Casting (Narrowing)
- Explicit Type Conversion is commonly referred to as 'Manual Type Conversion.' Conversion explicitly specified by the programmer.
- It refers to the manual conversion of a value from a larger data type to a smaller.
```java
double a = 10.5;
int b = (int) a;  // Needs manual conversion
```


🎯 Practice Task
Create a Java program that:
  - Declares variables of different data types
  - Prints their values
  - Try both implicit and explicit type casting

---

## 🔔 Stay Connected

- Subscribe to [JayantCodeCraft YouTube Channel](https://youtube.com/@JayantCodeCraft)
- Follow this GitHub repo for code, notes, and assignments
- Join the community and grow together 💬

---

## 🔜 Next Topic

➡️ **Control Statements in Java (if, else, switch, loops)**

---

> 💡 “Code karo, seekhte raho, aur shine karo!”  
> — Jayant, your coding buddy 🚀
> 
