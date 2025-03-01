# MyCalculator App

## Description
MyCalculator is a simple Android calculator application that supports basic arithmetic operations, including addition, subtraction, multiplication, division, and remainder calculation. The app features a clean user interface with a number pad and operation buttons.

## Features
- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)
- Remainder (%)
- Decimal input support
- Clear/Delete functionality

## Technologies Used
- Java
- Android SDK
- XML (UI Layout)
- JUnit (Testing)

## Installation
To run this project on your local machine:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/MyCalculator.git
   ```
2. Open the project in Android Studio.
3. Build and run the application on an emulator or a physical device.

## Usage
1. Enter numbers using the number pad.
2. Select an operation (+, -, *, /, %).
3. Press the `=` button to calculate the result.
4. Use the `C` button to clear the screen.

## Code Overview
The main functionality is implemented in `MainActivity.java`, where:
- Buttons are initialized and assigned click listeners.
- Arithmetic operations are handled.
- The result is displayed in a `TextView` component.

### Testing
The project includes unit testing using JUnit. The `ExampleUnitTest.java` file contains test cases to validate basic arithmetic operations. For example:
- The `addition_isCorrect()` test checks if the addition operation is functioning correctly by asserting `2 + 2 = 4`.

To run tests in Android Studio:
1. Open the `ExampleUnitTest.java` file.
2. Click the `Run` button next to the test method.
3. View test results in the `Run` window.

## Contributing
If you would like to contribute to this project:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push to your branch and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any questions or suggestions, feel free to reach out.

---
Enjoy using MyCalculator! 😊

