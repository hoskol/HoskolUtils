# HoskolUtils

HoskolUtils is a lightweight Java utility library that provides basic mathematical operations.  
It demonstrates principles of clean code, reusability, and modular design using interfaces and class implementation.

## 📦 Package
`com.hoskol.utils`

## ✨ Features
- `add(int a, int b)` - Adds two integers
- `multiply(int a, int b)` - Multiplies two integers
- `isPrime(int number)` - Checks if a number is a prime

## 🧩 Structure
- `MathUtils`: A class with static utility methods
- `IMathOperations`: An interface defining math operations
- `MathOperationsImpl`: A class implementing `IMathOperations`

## 🛠 How to Use

### Option 1: Add JAR to Classpath
Download the JAR file and include it in your Java project.

### Option 2: Use Source Code
Clone the repo and use the source files directly in your Java project.

### Sample Code
```java
import com.hoskol.utils.MathUtils;
import com.hoskol.utils.MathOperationsImpl;

public class TestApp {
    public static void main(String[] args) {
        // Using static utility method
        System.out.println("Sum: " + MathUtils.add(5, 7));

        // Using interface implementation
        MathOperationsImpl math = new MathOperationsImpl();
        System.out.println("Is 11 prime? " + math.isPrime(11));
    }
}
```

## 📚 Documentation
Full user documentation (Word format) is included in the repository under `HoskolUtils_Documentation_Updated.docx`.

## 🔗 Repository
This project is hosted at:  
[https://github.com/hoskol/HoskolUtils](https://github.com/hoskol/HoskolUtils)

## 👨‍💻 Author
Mohamad Hoskol
