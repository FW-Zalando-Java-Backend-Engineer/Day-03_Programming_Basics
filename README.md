### **📘 Day-03: Programming Basics in Java - Variables, Operators, Functions & Control Flow**  
Welcome to **Day-03** of our Java learning journey! Today, we will dive into core programming concepts, covering **variables, operators, functions, and control flow** to strengthen our foundation in Java.

---

## **📌 Lesson Structure**
### **1️⃣ Introduction to Programming in Java**
- What is **Programming**?
- Why choose **Java**?
- Understanding **Compilation vs Interpretation**.

### **2️⃣ Variables & Data Types**
- Declaring and Initializing Variables.
- **Primitive Data Types**: `int`, `double`, `char`, `boolean`, etc.
- **Reference Data Types**: `String`, Arrays, Objects.
- **Type Conversion** (Implicit & Explicit).

### **3️⃣ Operators in Java**
- **Arithmetic Operators** (`+`, `-`, `*`, `/`, `%`).
- **Relational Operators** (`==`, `!=`, `>`, `<`, `>=`, `<=`).
- **Logical Operators** (`&&`, `||`, `!`).
- **Bitwise Operators** (`&`, `|`, `^`, `~`, `<<`, `>>`, `>>>`).
- **Assignment & Compound Assignment** Operators (`+=`, `-=`, `*=`, etc.).
- **Increment (`++`) & Decrement (`--`) Operators**.

### **4️⃣ Control Flow Statements**
- **Selection Statements:**  
  - `if`, `if-else`, `if-else-if`, `switch-case`
- **Iteration Statements:**  
  - `for`, `while`, `do-while`
- **Jump Statements:**  
  - `break`, `continue`, `return`

### **5️⃣ Functions & Methods in Java**
- Understanding **Methods** in Java.
- **Declaring & Calling Methods**.
- **Return Types & Parameters**.
- **Method Overloading**.
- **Scope of Variables**.

### **6️⃣ Live Coding Exercises**
- **Simple Calculator** using Arithmetic Operators.
- **Finding the Largest of Three Numbers** using `if-else`.
- **A Loop-Based Number Pattern** using `for`.
- **Prime Number Checker** using Functions.

---

## **📜 Live Coding Examples**
### **🖥️ Declaring and Using Variables**
```java
public class VariablesDemo {
    public static void main(String[] args) {
        int age = 25;
        double price = 99.99;
        char grade = 'A';
        boolean isJavaFun = true;

        System.out.println("Age: " + age);
        System.out.println("Price: " + price);
        System.out.println("Grade: " + grade);
        System.out.println("Is Java fun? " + isJavaFun);
    }
}
```

### **🖥️ Arithmetic Operations**
```java
public class ArithmeticOperations {
    public static void main(String[] args) {
        int a = 10, b = 5;
        System.out.println("Addition: " + (a + b));
        System.out.println("Subtraction: " + (a - b));
        System.out.println("Multiplication: " + (a * b));
        System.out.println("Division: " + (a / b));
        System.out.println("Modulo: " + (a % b));
    }
}
```

### **🖥️ Using `if-else` to Find the Largest of Three Numbers**
```java
import java.util.Scanner;

public class LargestNumber {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter three numbers: ");
        int num1 = scanner.nextInt();
        int num2 = scanner.nextInt();
        int num3 = scanner.nextInt();

        int largest;
        if (num1 >= num2 && num1 >= num3) {
            largest = num1;
        } else if (num2 >= num1 && num2 >= num3) {
            largest = num2;
        } else {
            largest = num3;
        }

        System.out.println("Largest number is: " + largest);
        scanner.close();
    }
}
```

### **🖥️ Using Loops: Printing a Number Pattern**
```java
public class NumberPattern {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print(j + " ");
            }
            System.out.println();
        }
    }
}
```

### **🖥️ Prime Number Checker Using a Function**
```java
import java.util.Scanner;

public class PrimeNumberChecker {
    public static boolean isPrime(int number) {
        if (number <= 1) return false;
        for (int i = 2; i <= Math.sqrt(number); i++) {
            if (number % i == 0) return false;
        }
        return true;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int num = scanner.nextInt();

        if (isPrime(num)) {
            System.out.println(num + " is a prime number.");
        } else {
            System.out.println(num + " is not a prime number.");
        }

        scanner.close();
    }
}
```

---

## **🎯 Hands-on Exercises**
✅ **Modify the Simple Calculator** to also perform exponentiation (`Math.pow()`).  
✅ **Write a function** that checks whether a given number is even or odd.  
✅ **Create a multiplication table** using a loop and functions.  
✅ **Implement a method** that returns the factorial of a number.  

---

## **📚 Additional Resources**
- **[Official Java Documentation](https://docs.oracle.com/en/java/)**
- **[Java Operators Guide](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/opsummary.html)**
- **[Java Control Flow Statements](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/flow.html)**
- **[Functions & Methods in Java](https://docs.oracle.com/javase/tutorial/java/javaOO/methods.html)**
- **[Lesson Slides: Introduction to Programming with Java](https://github.com/FW-Zalando-Java-Backend-Engineer/Day-03_Programming_Basics/blob/main/Introduction%20to%20Programming%20with%20Java.pdf)**
- [Video Lesson Recording:](https://us06web.zoom.us/rec/share/lDa5cuHP31X-zq6oRvjShV0WiHL9Os5Mp2sWfrOO23SSAXyDl0D0S4MR95pizENL.VbjXDeSCDkGKOjCr?startTime=1742372114000)

---

🚀 **Great job preparing for tomorrow! Keep practicing and get ready for Day-04!** 💡🎉
