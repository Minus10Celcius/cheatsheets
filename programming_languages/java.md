# Basic Syntax

- Java is case-sensitive
- Class names start with a capital letter
- Method names start with a lowercase letter
- Use `;` at the end of every statement
- Code is written inside class and methods
- `main` method is the entry point of the program

## Variables

- Variables must be declared with a data type before use
- Data types and limitations:
  | Data Type | Size | Primitive/Reference | Value |
  | --------- | ---- | :-: | ----- |
  | `boolean` | 1 bit | primitive | `true` or `false` |
  | `int` | 4 bytes | primitive | -2 billion to 2 billion |
  | `float` | 4 bytes | primitive | up to 6-7 digits; must suffix 'f' to the number |
  | `double` | 8 bytes | primitive | up to 15 digits |
  | `char` | 2 bytes | primitive | single character/letter/ASCII |
  | `String` | varies | reference | sequence of characters |
  | `byte` | 1 byte | primitive | -128 to 127 |
  | `short` | 2 bytes | primitive | -32,768 to 32,767 |
  | `long` | 8 bytes | primitive | -9 quintillion to 9 quintillion |
- Use `final` keyword to declare immutable constants
- Examples:

```java
  String name = "John";
  int age = 30;
  float salary = 25000.50f;
  double tax = 10.00;
  char gender = 'M';
  boolean isMarried = true;
```

## Operators

- Arithmetic operators: `+`, `-`, `*`, `/`, `%`
- Relational operators: `==`, `!=`, `>`, `<`, `>=`, `<=`
- Logical operators: `&&`, `||`, `!`
- Assignment operators: `=`, `+=`, `-=`, `*=`, `/=`, `%=`

## Conditional Statements

- `if` statement
- `if-else` statement
- `switch` statement

## Loops

- `for` loop
- `while` loop
- `do-while` loop

## Arrays

- Array is a collection of similar data types
- Array index starts from `0`
- Examples:

```java
  int[] marks = new int[5];
  marks[0] = 85;
  marks[1] = 90;
  marks[2] = 80;
```

## Methods

- Reusable blocks of code
- Can accept parameters and return values
- Examples:

```java
  public int addNumbers(int a, int b) {
      return a + b;
  }
  public void sayHello() {
      System.out.println("Hello");
  }
```

## Classes

- Blueprint for creating objects
- Variables and methods inside a class
- Examples:

```java
  class Student {
      int rollNo;
      String name;
      void displayDetails() {
          System.out.println("Roll No: " + rollNo);
          System.out.println("Name: " + name);
      }
  }
```
