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
✅ JDK, JRE, JVM - definitions and differences
✅ Installed JDK and Eclipse
✅ Wrote and ran your first Java program
✅ Understood structure of Java code

---


## 🔔 Stay Connected

- Subscribe to [JayantCodeCraft YouTube Channel](https://youtube.com/@JayantCodeCraft)
- Follow this GitHub repo for code, notes, and assignments
- Join the community and grow together 💬

---

## 🔜 Next Topic

➡️ **Java Programming Basics: Keywords, Identifiers, Variables, and Data Types**

---

> 💡 “Code karo, seekhte raho, aur shine karo!”  
> — Jayant, your coding buddy 🚀
> 
