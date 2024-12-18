# Basic_Java_Calculator

This project is a simple graphical user interface (GUI) calculator built using Java's AWT and Swing libraries. The calculator supports basic arithmetic operations like addition, subtraction, multiplication, division, and square root calculations.

## Features

- Basic arithmetic operations: Addition, Subtraction, Multiplication, Division
- Square root calculation: A button to calculate the square root of a number.
- Clear screen: Clears the current input.
- Menu options: Includes file-related menu options like "New File", "Save", and "Exit".

## Requirements

 Java 8 or higher: The project is developed using Java AWT and Swing components.

# Running the Application

## 1. Clone the repository:
git clone `https://github.com/anujayavidmal2002/Basic_Java_Calculator.git`

## 2. Navigate to the project directory:

bash `cd Basic_Java_Calculator`

## 3. Compile the Java files:

bash `javac -d bin src/GUI/*.java`

## 4. Run the application:

bash `java -cp bin GUI.Basiccal`

This will launch the calculator GUI.


## Features in Detail

- Buttons for digits (0-9): These buttons allow users to input numbers into the text field.
- Operations: Buttons for +, -, *, and / let the user perform calculations.
- Square Root: The √ button calculates the square root of the entered number.
- Clear Button: Clicking the C button clears the input.
- Equal Button (=): This performs the calculation based on the operation selected.
- Menu Options: Includes "New File", "Save", and "Exit" options in the menu.

  
## Code Structure

- Basiccal: The main class that initializes and runs the application.
- calbody: The main GUI frame that includes all the calculator buttons, text fields, and logic for performing calculations.
- Action Listeners: Each button has an associated ActionListener that defines the behavior when the button is pressed.

