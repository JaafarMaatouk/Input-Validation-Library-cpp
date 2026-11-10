# Input Validation Library (C++)

A modular, reusable C++ library designed to handle robust input validation and complex data manipulations. Built using Object-Oriented Programming (OOP), this library provides utility classes for validating user inputs and managing dates and strings efficiently.

## Project Overview
This library is designed to be integrated into larger C++ applications to prevent invalid user inputs and handle data formatting gracefully. It saves developers time by abstracting away complex validation logic (like leap years and date comparisons) into easy-to-use classes.

## Key Features
- **Date Management (`clsDate`):**
  - Accurate comparison between dates (Before, After, Equal).
  - Handles leap years and varying month lengths.
  - Calculates days of the week and period overlaps.
- **Input Validation (`clsInputValidate`):**
  - Validates numeric inputs (integers, doubles) within specific ranges.
  - Ensures the user enters valid data types and prevents program crashes from bad input.
- **String Utilities (`clsString`):**
  - Handles string manipulations, formatting, and parsing.

## Architecture & Technical Highlights
- **Object-Oriented Design:** Encapsulation of validation logic within dedicated classes.
- **Optimized Logic:** Implements efficient decision-making (e.g., if a date is neither before nor equal, it returns "After" directly, avoiding unnecessary function calls).
- **Modularity:** Separated into clean header files (`dsDate.h`, `dsString.h`, `dsInputValidate.h`) for easy integration into any project.

## How to Run
1. Clone this repository or download it as a ZIP file.
2. Open the `.sln` file in Visual Studio.
3. The library is ready to be included in other projects. You can run the `main` file to test the validation functions.
4. Press `F5` or `Ctrl + F5` to build and test.

## License
This project is open-source and available under the MIT License.
