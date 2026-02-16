# CPP Module 00 - Specificities of C++ vs C


**A first step into the world of Object-Oriented Programming (OOP), transitioning from procedural C to class-based C++ while mastering basic I/O and namespaces.**



## 🧠 Key Learning Objectives

* **🟢 Namespaces & I/O Streams**: Learning to use `std::cout`, `std::cin`, and `std::endl` instead of `printf`/`scanf`.
* **🔵 Class & Instance**: Understanding the basic structure of a class and how to instantiate objects.
* **🟡 Encapsulation**: Using `private` and `public` access specifiers to protect data.
* **🔴 Static Members**: Discovering how to use static attributes and methods to share data across all instances of a class.




## 📂 Exercise Breakdown

### 🟢 Ex00: Megaphone
* **Goal**: A simple exercise to get used to the `c++` compiler and basic output.
* **Concepts**:
    * Handling command-line arguments.
    * Character manipulation (converting strings to uppercase).
    * Basic usage of `std::cout`.

### 🔵 Ex01: My Awesome PhoneBook
* **Goal**: Create a small, interactive 8-contact phonebook.
* **Concepts**:
    * **Class Design**: Creating `Contact` and `PhoneBook` classes.
    * **Interactive Loops**: Handling user input commands (ADD, SEARCH, EXIT).
    * **Data Formatting**: Truncating and aligning text to fit a 10-column table display.
    * **Input Validation**: Ensuring the program doesn't crash on empty fields or EOF.

### 🟡 Ex02: The Job of Your Dreams
* **Goal**: Reconstruct a class from a provided log file and header.
* **Concepts**:
    * **Log Analysis**: Understanding how to match program output with function logic.
    * **Static Data**: Using static variables to track global bank information (total deposits, number of accounts, etc.).
    * **Time Formatting**: Implementing custom timestamps for log entries using `<ctime>`.



## 🚀 Technical Requirements
* **Standard**: C++ 98 (`-std=c++98`).
* **Compiler**: `c++` with flags `-Wall -Wextra -Werror`.
* **Prohibited**: No `using namespace std;` allowed. Use explicit scoping (e.g., `std::string`).
* **Style**: Code must be clean, readable, and follow the standard C++ class separation (`.hpp` for definition, `.cpp` for implementation).

