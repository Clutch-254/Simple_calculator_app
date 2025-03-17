# Calculator Application

This is a simple calculator application built using Java and the Swing library. The calculator provides basic arithmetic operations such as addition, subtraction, multiplication, and division, along with additional functionalities like decimal input, negation, deletion, and clearing the input field.

## Features

- **Basic Arithmetic Operations**: Addition (+), Subtraction (-), Multiplication (*), Division (/).
- **Decimal Input**: Allows input of decimal numbers.
- **Negation**: Toggles the sign of the current number.
- **Delete**: Removes the last character from the input field.
- **Clear**: Clears the entire input field.
- **Equals (=)**: Computes the result of the current operation and displays it.

## How to Use

1. **Running the Application**:
   - Ensure you have Java installed on your system.
   - Compile the Java file using the command:
     ```bash
     javac calculator.java
     ```
   - Run the compiled class file:
     ```bash
     java calculator
     ```

2. **Using the Calculator**:
   - **Number Buttons (0-9)**: Click to input numbers.
   - **Decimal Button (.)**: Click to input a decimal point.
   - **Operator Buttons (+, -, *, /)**: Click to select the desired arithmetic operation.
   - **Equals Button (=)**: Click to compute and display the result.
   - **Negation Button (-)**: Click to toggle the sign of the current number.
   - **Delete Button**: Click to remove the last character from the input field.
   - **Clear Button**: Click to clear the entire input field.

## Code Structure

- **JFrame**: The main window of the application.
- **JTextField**: Displays the current input and result.
- **JButton**: Buttons for numbers, operators, and other functionalities.
- **JPanel**: Organizes the buttons in a grid layout.
- **ActionListener**: Handles button click events and performs the corresponding actions.

## Example

1. **Addition**:
   - Input: `5 + 3`
   - Click `=` to get the result: `8`

2. **Subtraction**:
   - Input: `10 - 4`
   - Click `=` to get the result: `6`

3. **Multiplication**:
   - Input: `7 * 3`
   - Click `=` to get the result: `21`

4. **Division**:
   - Input: `20 / 5`
   - Click `=` to get the result: `4`

5. **Negation**:
   - Input: `5`
   - Click `-` to get the result: `-5`

6. **Delete**:
   - Input: `123`
   - Click `Delete` to get the result: `12`

7. **Clear**:
   - Input: `123`
   - Click `Clear` to get the result: `` (empty field)

## Customization

- **Font**: The font used for the buttons and text field can be customized by modifying the `myfont` variable.
- **Layout**: The layout and size of the buttons and text field can be adjusted by modifying the `setBounds` and `GridLayout` parameters.

## Dependencies

- **Java Development Kit (JDK)**: Ensure you have JDK installed to compile and run the application.
- **Swing Library**: The application uses the Swing library, which is part of the standard Java SE platform.

## License

This project is open-source and available under the MIT License. Feel free to modify and distribute it as per the license terms.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Contact

For any questions or suggestions, please open an issue on the GitHub repository or contact me directly.


Enjoy using the calculator!
