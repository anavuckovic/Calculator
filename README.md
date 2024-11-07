# Calculator

A simple yet functional calculator web application built with HTML, CSS, and JavaScript. The calculator supports basic arithmetic operations such as addition, subtraction, multiplication, and division, and features a dark/light theme toggle.

Features:
  Basic Arithmetic Operations: Perform simple calculations including addition, subtraction, multiplication, and division.
  Backspace Function: Allows you to delete the last character in the input.
  Clear Function: Clears the current input.
  Dark/Light Theme Toggle: Switch between a dark and light theme for the calculator interface.
  Responsive Design: The layout is responsive and works on both mobile and desktop devices.

Tech Stack:
  HTML: Provides the structure for the calculator interface.
  CSS: Styles the calculator and implements the dark and light themes.
  JavaScript: Handles the logic for the calculator’s operations, backspace, and theme toggling.

Installation:
To run the Calculator on your local machine, follow these steps:
1. Clone the repository: git clone https://github.com/yourusername/calculator.git
2. Navigate to the project directory: cd calculator
3. Open index.html in a web browser: You can double-click the index.html file to open the project in your default browser.
Alternatively, use a local server (such as Live Server in Visual Studio Code) for a better development experience.

Usage:
  Basic Operations: Click the buttons on the calculator interface to perform basic arithmetic operations.
  Clear: Click the C button to clear the display.
  Backspace: Click the < button to delete the last entered character.
  Equal: Click the = button to calculate the result of the expression entered.
  Dark/Light Theme Toggle: Click the circular icon in the top right corner to switch between the dark and light themes.

Dependencies: No external libraries or frameworks are used in this project. It is built using vanilla HTML, CSS, and JavaScript.

Credits:
  Tutorial: The project was created based on a tutorial by the Not Only Dev YouTube channel.
Icons: No external icon libraries are used for the buttons, but custom icons are included for the theme toggle.

Key Files:
  index.html: Contains the structure and layout of the calculator interface, including buttons for numbers and operations.
  style.css: Provides styling for the calculator and defines the light and dark themes. It also contains styling for button hover effects.
  script.js: Contains the JavaScript logic to handle the calculator's functionality. It listens for button clicks, performs arithmetic calculations, handles backspace functionality, 
  and toggles between light and dark themes.

How It Works:
  Button Event Listeners: The JavaScript code listens for clicks on calculator buttons. When a number or operator button is clicked, it is added to the display screen.
  Clear Button: When the C button is clicked, it clears the screen.
  Backspace Button: The < button removes the last character from the display text.
  Equal Button: The = button evaluates the expression and shows the result. If the input is empty, it displays an error message "Empty!" for 2 seconds.
  Theme Toggle: The theme toggle button switches between the dark and light themes by toggling the dark class on the calculator container.


Feel free to modify the project or contribute to the repository. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request!
