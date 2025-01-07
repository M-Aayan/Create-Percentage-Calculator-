# Create-Percentage-Calculator

The Percentage Calculator is a simple web-based application built using HTML, CSS, and JavaScript. It allows users to calculate the percentage of a given number by entering the necessary inputs through prompts. The result is displayed using an alert, making the tool interactive and user-friendly.
How It Performs


User Interaction:

When the page is loaded, the user is prompted via prompt() to input two values:
The numerator (part of the total for which the percentage is calculated).
The denominator (the total value).
The user inputs the values into the prompts as directed.


Calculation:

JavaScript performs the percentage calculation using the formula:
Percentage=(Numerator/Denominator)×100

Result Display:
The calculated percentage is displayed using alert(), providing immediate feedback to the user.

Error Handling:
If the user inputs invalid or non-numeric values, the program can handle these gracefully by showing an error message using alert().


How It Was Made


HTML:
Provides the basic structure for the calculator, such as a simple button to trigger the calculation process using JavaScript.
Minimal styling is applied for visual enhancement.


CSS:
Used to style the button and make the interface visually appealing.
Background, font styles, and hover effects are applied to enhance user experience.
JavaScript:

Prompt for Input: The prompt() function is used to gather user input for the numerator and denominator.

Calculation Logic: Basic mathematical operators (/ and *) are used to perform the percentage calculation.

Display Result: The alert() function is used to show the result to the user.

Validation: Simple checks ensure valid input, such as avoiding division by zero or invalid characters.
