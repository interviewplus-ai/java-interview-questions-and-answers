# Java Interview Questions And Answers

Most targeted up-to-date Java interview questions and answers list

# Table of Contents

1. [What is the difference between `==` and `.equals()` in Java?](#1-what-is-the-difference-between--and-equals-in-java)
2. [How do you create and start a new thread in Java?](#2-how-do-you-create-and-start-a-new-thread-in-java)
3. [What is the difference between `ArrayList` and `LinkedList` in Java?](#3-what-is-the-difference-between-arraylist-and-linkedlist-in-java)
4. [How do you handle exceptions in Java?](#4-how-do-you-handle-exceptions-in-java)
5. [How do you implement inheritance in Java?](#5-how-do-you-implement-inheritance-in-java)
6. [How do you perform file I/O operations in Java?](#6-how-do-you-perform-file-io-operations-in-java)
7. [What is the purpose of the static keyword in Java?](#7-what-is-the-purpose-of-the-static-keyword-in-java)
8. [How do you implement an interface in Java?](#8-how-do-you-implement-an-interface-in-java)
9. [How do you handle multithreading synchronization in Java?](#9-how-do-you-handle-multithreading-synchronization-in-java)
10. [How do you sort elements in an array in Java?](#10-how-do-you-sort-elements-in-an-array-in-java)
11. [What is the purpose of the final keyword in Java?](#11-what-is-the-purpose-of-the-final-keyword-in-java)
12. [How do you work with dates and times in Java?](#12-how-do-you-work-with-dates-and-times-in-java)
13. [How do you handle collections in Java?](#13-how-do-you-handle-collections-in-java)
- [Whats more?](#whats-more)
- [Contributing](#contributing)
- [License](#license)

## 1. What is the difference between '==' and '.equals()' in Java?

```java
String str1 = "Hello";
String str2 = "Hello";

boolean result1 = (str1 == str2); // Comparing references
boolean result2 = str1.equals(str2); // Comparing values

System.out.println(result1); // true
System.out.println(result2); // true
```

## 2. How do you create and start a new thread in Java?

```java
Thread thread = new Thread(() -> {
    // Thread logic here
});

thread.start();
```

## 3. What is the difference between ArrayList and LinkedList in Java?

```java
ArrayList<String> arrayList = new ArrayList<>();
LinkedList<String> linkedList = new LinkedList<>();

arrayList.add("Element 1");
linkedList.add("Element 2");
```

## 4. How do you handle exceptions in Java?

```java
try {
    // Code that may throw an exception
} catch (Exception e) {
    // Exception handling logic
}
```

## 5. How do you implement inheritance in Java?

```java
class Parent {
    // Parent class code
}

class Child extends Parent {
    // Child class code
}
```

## 6. How do you perform file I/O operations in Java?

```java
import java.io.*;

try {
    File file = new File("file.txt");
    BufferedReader reader = new BufferedReader(new FileReader(file));

    String line;
    while ((line = reader.readLine()) != null) {
        // Process each line
    }

    reader.close();
} catch (IOException e) {
    // Exception handling
}
```

## 7. What is the purpose of the static keyword in Java?

```java
class MyClass {
    static int myStaticVariable = 10;
    static void myStaticMethod() {
        // Static method logic
    }
}
```

## 8. How do you implement an interface in Java?

```java
interface MyInterface {
    void myMethod();
}

class MyClass implements MyInterface {
    public void myMethod() {
        // Interface method implementation
    }
}
```

## 9. How do you handle multithreading synchronization in Java?

```java
class Counter {
    private int count;

    public synchronized void increment() {
        count++;
    }
}
```

## 10. How do you sort elements in an array in Java?

```java
import java.util.Arrays;

int[] array = {5, 2, 8, 1, 6};

Arrays.sort(array);
```

## 11. What is the purpose of the final keyword in Java?
java
Copy code
final int myVariable = 10;
final void myMethod() {
    // Final method logic
}


## 12. How do you work with dates and times in Java?

```java
import java.time.LocalDate;
import java.time.format.DateTimeFormatter;

LocalDate date = LocalDate.now();
String formattedDate = date.format(DateTimeFormatter.ofPattern("yyyy-MM-dd"));
```

## 13. How do you handle collections in Java?

```java
import java.util.ArrayList;
import java.util.List;

List<String> list = new ArrayList<>();
list.add("Element 1");
list.add("Element 2");
```

## What's more?
<a href="https://interviewplus.ai/developers-and-programmers/java/questions">A comprehensive list of questions and answers</a>

## Contributing
We welcome contributions from our users to help make this resource as comprehensive and useful as possible. If you have been recently interviewed and encountered a question that is not currently covered on our website, feel free to suggest it as a new question. Your contributions will be added to our platform, and we will make sure to credit you for your contributions. We appreciate your help in making our platform a valuable tool for all job seekers.

## License
MIT License


