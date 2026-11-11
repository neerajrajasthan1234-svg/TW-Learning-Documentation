
# Doxygen Documentation

## 1. Introduction to Doxygen

Doxygen is a documentation generation tool used to automatically create documentation from specially formatted comments in source code. It supports programming languages such as C, C++, Java, Python, and others.

## 2. Features of Doxygen

- Automatically generates documentation.
- Supports C and C++ programs.
- Generates HTML and LaTeX documentation.
- Supports classes, functions, variables, and files.
- Creates class diagrams and dependency graphs.
- Helps developers understand and maintain code.

## 3. Installation of Doxygen

On macOS, Doxygen can be installed using Homebrew.

```bash
brew install doxygen
```

Check the installed version:

```bash
doxygen --version
```

## 4. Types of Documentation Comments

Doxygen supports special comment styles.

### Single-line documentation

```cpp
/// This function adds two numbers.
int add(int a, int b);
```

### Multi-line documentation

```cpp
/**
 * @brief Adds two numbers.
 * @param a First number.
 * @param b Second number.
 * @return Sum of the numbers.
 */
int add(int a, int b);
```

## 5. Important Doxygen Commands

| Command | Purpose |
|---|---|
| `@brief` | Short description |
| `@param` | Describes function parameters |
| `@return` | Describes return value |
| `@author` | Specifies author |
| `@date` | Specifies date |
| `@file` | Describes a file |
| `@class` | Describes a class |
| `@details` | Provides detailed description |

## 6. Example of Doxygen in C++

```cpp
/**
 * @file calculator.cpp
 * @brief Simple calculator program.
 * @author Neeraj Kumar
 */

#include <iostream>
using namespace std;

/**
 * @brief Adds two integers.
 * @param a First integer.
 * @param b Second integer.
 * @return Sum of a and b.
 */
int add(int a, int b) {
    return a + b;
}

int main() {
    cout << add(10, 20);
    return 0;
}
```

## 7. Generating Documentation

Follow these steps:

1. Create a Doxyfile configuration file.

```bash
doxygen -g
```

2. Open and configure the Doxyfile.

3. Set the input source files.

4. Enable HTML output.

5. Generate documentation.

```bash
doxygen Doxyfile
```

6. Open the generated HTML documentation from the html folder.

## 8. Output Formats

Doxygen can generate:

- HTML documentation.
- LaTeX documentation.
- PDF documentation (through LaTeX).
- Man pages.
- XML output.

## 9. Advantages of Doxygen

- Saves time in documentation.
- Improves code readability.
- Makes project maintenance easier.
- Helps in team collaboration.
- Keeps documentation close to source code.

## 10. Conclusion

Doxygen is a useful documentation tool that generates structured documentation from source code comments. It helps developers maintain professional and understandable software projects.
