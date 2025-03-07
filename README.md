# Basic Calculator with GUI

A simple calculator application with a graphical user interface (GUI) built using Python and the `tkinter` library.

## Features

- **Basic Operations**: Supports addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`).
- **Clear Functionality**: Includes a "C" button to clear the input field.
- **Error Handling**: Displays "Error" for invalid expressions.
- **User-Friendly Interface**: Buttons are arranged in a grid layout for easy use.


## How to Run

1. **Install Python**: Make sure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/).

2. **Run the Script**:
   - Save the script as `calculator_gui.py`.
   - Open a terminal or command prompt.
   - Navigate to the directory where the script is saved.
   - Run the script using the following command:
     ```bash
     python calculator_gui.py
     ```

3. **Use the Calculator**:
   - Click the buttons to enter numbers and operators.
   - Press "=" to calculate the result.
   - Press "C" to clear the input field.

## Code Overview

The script uses the `tkinter` library to create the GUI. Here's a brief overview of the code:

- **Input Field**: Displays the current expression or result.
- **Buttons**: Arranged in a 4x4 grid for numbers, operators, and special functions.
- **Event Handling**: Button clicks are handled by the `button_click` function, which updates the input field or calculates the result.

## Requirements

- Python 3.x
- `tkinter` (comes pre-installed with Python)

## Author

MD Mahbub Islam

## License

This project is open-source and available under the MIT License.
