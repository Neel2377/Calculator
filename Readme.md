Link: https://basic-calculator-tan.vercel.app/

1.Addition
![alt text](Output/calcu1.png)

2.Subtraction
![alt text](Output/cal2.png)

3.Multiplication
![alt text](Output/cal3.png)

4.Divison
![alt text](Output/cal4.png)

<-Calculator->
![alt text](Output/cal.png)
Calculator Documentation

This document provides an overview of a simple calculator application built using HTML, CSS, and JavaScript. The calculator allows users to perform basic arithmetic operations: addition, subtraction, multiplication, and division.

HTML Structure

The HTML structure consists of the following main components:

DOCTYPE Declaration: Specifies the document type and version of HTML.

Head Section: Contains metadata, links to stylesheets, and the title of the document.

Body Section: Contains the main content of the calculator, including input fields, buttons, and result display.

Key Components

Head Section:

Sets the character encoding to UTF-8.
Configures the viewport for responsive design.
Links to Bootstrap CSS for styling.
Links to an external CSS file (style.css).
Body Section:

Container: A Bootstrap container to center the calculator.

Calculator Title: Displays "CALCULATOR".

Input Fields: Two number inputs for user input.

Buttons: Four buttons for arithmetic operations and a clear button.

Result Field: Displays the result of the calculations, set to read-only.

JavaScript Functions

The calculator relies on JavaScript functions to perform calculations. The following functions are expected to be defined in the script.js file:

sum(): Adds the two input numbers.

sub(): Subtracts the second number from the first.

mul(): Multiplies the two input numbers.

div(): Divides the first number by the second.

cle(): Clears the input fields and the result.

Error Handling

The application may encounter a 404 error when trying to load Bootstrap CSS from the CDN. Ensure the URL is correct or consider using a local copy of Bootstrap.

Conclusion

This simple calculator application provides a user-friendly interface for performing basic arithmetic operations. Ensure that the JavaScript functions are correctly implemented in the script.js file for full functionality.

Bookmark message
Copy
