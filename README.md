# Java OOP Calculator

A Java console calculator built around a `Calculator` class with getters and setters.

## Features

- Add, subtract, multiply and divide two numbers
- The menu loops until you choose 0 to exit
- Catches `InputMismatchException` for input that is not a number

> **Note (TODO):** the file is named `calculator.java` but holds `public class Calculator`. Java needs the names to match, so rename it to `Calculator.java` to compile on case-sensitive systems.

## Tech stack

Java 14+ (uses `switch` arrow syntax)

## Getting started

```bash
git clone https://github.com/Matiz009/java-oop-calculator.git
cd java-oop-calculator
mv calculator.java Calculator.java   # needed on Linux/macOS
javac Calculator.java TestCalculator.java
java TestCalculator
```

## Project structure

```
calculator.java       Calculator class
TestCalculator.java   Console menu
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
