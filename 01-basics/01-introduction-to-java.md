# Java Programming — 01: Introduction to Java

## What is Java?

Java is a high-level, object-oriented, class-based programming language designed to be portable, reliable, and widely used for building applications.

## Why Learn Java?

- Object-oriented programming
- Platform independent through the JVM
- Strong type system
- Large ecosystem and community
- Used in web, enterprise, Android, backend, and many other applications

## JDK, JRE, and JVM

### JVM — Java Virtual Machine

The JVM runs Java bytecode and provides platform independence.

### JRE — Java Runtime Environment

The JRE provides the components needed to run Java applications, including the JVM and standard libraries.

### JDK — Java Development Kit

The JDK contains development tools such as the Java compiler (`javac`) along with the runtime components.

## First Java Program

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```

## Understanding the Program

- `public class Main` defines a class named `Main`.
- `main()` is the entry point of a Java application.
- `String[] args` stores command-line arguments.
- `System.out.println()` prints text to the console.

## Compile and Run

```bash
javac Main.java
java Main
```

Output:

```text
Hello, Java!
```

## Key Takeaway

Java source code is compiled into bytecode, which can run on a JVM. This is the foundation of Java's famous **"write once, run anywhere"** approach.

## Practice

1. Change the output to print your name.
2. Print three lines about yourself.
3. Create a second Java class and print a message from it.

---

**Series:** Java Programming — Basics to Advanced  
**Part:** 01 — Introduction to Java
