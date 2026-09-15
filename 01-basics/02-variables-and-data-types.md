# Java Programming — 02: Variables and Data Types

## What is a Variable?

A variable is a named memory location used to store a value.

```java
int age = 21;
String name = "Dishan";
```

Here, `age` stores an integer and `name` stores text.

## Basic Syntax

```java
dataType variableName = value;
```

Example:

```java
double price = 1499.50;
boolean isStudent = true;
```

## Java Primitive Data Types

| Type | Example | Description |
|---|---|---|
| `byte` | `100` | Small integer |
| `short` | `10000` | Integer |
| `int` | `50000` | Common integer type |
| `long` | `500000L` | Large integer |
| `float` | `5.5f` | Decimal number |
| `double` | `19.99` | More precise decimal |
| `char` | `'A'` | Single character |
| `boolean` | `true` | True or false |

## Reference Type Example

`String` is a commonly used reference type:

```java
String language = "Java";
```

## Declaring and Updating Variables

```java
int score = 80;
score = 95;

System.out.println(score);
```

Output:

```text
95
```

## Constants with `final`

Use `final` when a variable should not be reassigned.

```java
final double PI = 3.14159;
```

After initialization, `PI` cannot be assigned another value.

## Type Casting

### Widening Casting

Automatically converts a smaller compatible numeric type to a larger one.

```java
int number = 10;
double value = number;
```

### Narrowing Casting

Requires an explicit cast and may lose information.

```java
double price = 19.99;
int whole = (int) price;
```

`whole` becomes `19`.

## Complete Example

```java
public class Main {
    public static void main(String[] args) {
        String name = "Dishan";
        int age = 21;
        double height = 5.8;
        boolean student = true;
        char grade = 'A';

        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Height: " + height);
        System.out.println("Student: " + student);
        System.out.println("Grade: " + grade);
    }
}
```

## Practice

1. Create variables for your name, age, college, and GPA.
2. Calculate the area of a rectangle using `double` variables.
3. Create a `final` variable for the value of PI.
4. Try converting a `double` to an `int` using casting.

## Key Takeaway

Choosing the correct data type helps your Java programs represent data clearly and use memory efficiently. Understanding variables and types is essential before moving into operators, input, and control flow.

---

**Series:** Java Programming — Basics to Advanced  
**Part:** 02 — Variables and Data Types
