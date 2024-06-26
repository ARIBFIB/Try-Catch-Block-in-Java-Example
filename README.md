# Try-Catch-Block-in-Java-Example
This project demonstrates the usage of the try-catch block in Java, which is a powerful mechanism for handling exceptions and ensuring the stability and robustness of your application.
# Try-Catch Block in Java
![How it works (7)](https://github.com/ARIBFIB/Try-Catch-Block-in-Java-Example/assets/125716994/9e8cc351-a5fd-4cf3-8e2c-81d6417c9442)

<p align="center">
  <img src="https://github.com/your-username/try-catch-block/blob/main/logo.png" alt="Project Logo" width="200" height="200">
</p>
# Code

```
public class tryCatchBlock {
    public static void main(String[] args) {
        int num1 , num2;
        try {
            num1 = 0;
            num2 = 62 / num1;
            System.out.println(num2);
            System.out.println("Hey I am at the end of try block");
        } catch (ArithmeticException e) {
            System.out.println("Exception ocured");
            System.out.println("I'm out of try-catch block in Java");
        }
    }
}
```
# Output
![image](https://github.com/ARIBFIB/Try-Catch-Block-in-Java-Example/assets/125716994/e1f374d0-d27d-43e7-b81f-8a563875318b)


[![MIT License][]](https://opensource.org/licenses/MIT)

The Try-Catch Block in Java is a powerful mechanism for handling exceptions and ensuring the stability and robustness of your application. This repository provides a comprehensive example that demonstrates the usage of the try-catch block to handle an `ArithmeticException`.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Demonstration](#demonstration)
- [License](#license)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction

In Java, exceptions are events that occur during the execution of a program that disrupt the normal flow of the program's instructions. The try-catch block is a way to handle these exceptions and prevent your program from crashing.

The `try` block contains the code that might throw an exception, and the `catch` block contains the code that handles the exception. If an exception is thrown within the `try` block, the program will immediately jump to the `catch` block, which can then handle the exception and continue the program's execution.

## Features

- Handles `ArithmeticException` by catching and printing a message to the console.
- Demonstrates the proper structure and usage of the try-catch block in Java.
- Ensures the stability and robustness of the application by gracefully handling exceptions.
- Provides a clear example for understanding the exception handling mechanism in Java.

## Installation

To use this project, simply clone the repository to your local machine:```
git clone https://github.com/your-username/try-catch-block.git```

Alternatively, you can download the project as a ZIP file and extract it to your desired location.

## Usage

To run the example code, navigate to the project directory and compile the Java file:```
javac tryCatchBlock.java```

Then, run the compiled class:```
java tryCatchBlock```

This will execute the code and demonstrate the usage of the try-catch block.

## Demonstration

Check out the following YouTube video for a detailed walkthrough of the project:[![Try-Catch Block in Java Demo][]][https://www.youtube.com/watch?v=XXXXXXXXXX](https://youtu.be/n6CT0JNlgsA)

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to create a new issue or submit a pull request.

## Contact

If you have any questions or feedback, you can reach me at:

- Email: [your-email@example.com](mailto:your-email@example.com)
- GitHub: [your-github-username](https://github.com/your-github-username)
