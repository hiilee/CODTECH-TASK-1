# CODTECH-TASK-1
NAME: Lijo John

COMPANY: CODTECH IT SOLUTIONS

ID: CT12DS566

DOMAIN:Cybersecurity and Ethical Hacking

DURATION:10th june 2024 to 10th August 2024

OBJECTIVE OF THE PROJECT

The objective of the provided Python code is to assess the strength of a given password based on certain criteria. It evaluates the password against the following criteria:

Length: Should be 8 characters or more.
Uppercase Letter: Should contain at least one uppercase alphabetical character.
Lowercase Letter: Should contain at least one lowercase alphabetical character.
Number: Should contain at least one numeric digit.
Special Character: Should contain at least one special character (non-alphanumeric).
Based on how many of these criteria the password meets, it categorizes the strength of the password into five levels: Very Weak, Weak, Moderate, Strong, and Very Strong.

Activities:

Importing Modules: The code starts by importing the re module for regular expressions.
Function Definition (assess_password_strength):

Defines a function assess_password_strength that takes a password as input and evaluates it against the specified criteria using regular expressions.
Checks each criterion using regular expressions to determine if the password contains the required characters or meets the length requirement.
Calculates criteria_met which counts how many criteria the password satisfies.
Determines the strength of the password based on criteria_met.
Constructs a feedback dictionary providing detailed feedback on which criteria the password meets or fails.
Main Function (main):

Implements an interactive loop (while True:) where the user can input passwords to assess.
Displays a menu and prompts the user to enter a password.
Evaluates the entered password using assess_password_strength.
Prints the strength level of the password (Very Weak, Weak, Moderate, Strong, or Very Strong).
Outputs feedback for each criteria (whether it's met or not).
Allows the user to exit the program by typing 'exit'.

Conclusion:

The code effectively provides a basic password strength assessment tool that:

Checks for minimum length and presence of various character types in a password.
Provides clear feedback on which criteria the password meets or fails.
Uses regular expressions for pattern matching, making it flexible and efficient for checking character types.
Implements a simple interactive interface allowing users to assess multiple passwords until they choose to exit.
Improvements could include adding more advanced criteria or integrating with a password policy enforcement system for more robust security assessment.
