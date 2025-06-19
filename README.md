# C++-Fish-Validation-System
A C++ console app that validates fishing catches based on Australian maritime rules. Uses OOP design and Mediator Pattern via SeaPlusPlusEngine to enforce species- and group-specific size, egg, and bag rules. The code was run in the Clion CLI interface.

# SeaPlusPlus Fish Validation System

SeaPlusPlus is a C++ console application that simulates a real-world fish validation system based on Australian fishing regulations. It uses an object-oriented design and the Mediator Pattern to enforce size, egg-carrying, and bag limits for different marine species.

## 🎯 Features

- 🐟 Validates individual catches based on species rules
- 📦 Supports **Bag input**: validate multiple fish at once
- 📁 Loads all fish regulation data dynamically from a CSV file
- 👨‍✈️ Uses a Mediator pattern (`SeaPlusPlusEngine`) to centralize validation
- 📜 Displays notes and exceptions like "release-only" or "no size rules"
- ✅ Handles special cases:
  - No size + no egg rule
  - Only minimum length rule
  - Maximum or minimum length checks
  - Species carrying eggs
- 🚫 Provides immediate feedback if any rule is violated
- 🧠 Clean and modular C++ architecture

## 🛠️ Technologies

- C++
- Standard Template Library (STL)
- File I/O (CSV parsing)
- Clion

## 🚀 How to Run

1. Clone the repository
2. Open in **CLion** or any C++ IDE
3. Build and run the `App.cpp`
4. Follow the console prompts to validate your catches
