## Python Basics: f-Strings and Life in Weeks Program
This repository contains Python programs demonstrating the use of f-strings for string formatting and a program to calculate the number of weeks left until the age of 90.

# Description
This project includes an introduction to f-strings in Python and a "Life in Weeks" program that calculates how many weeks you have left if you live until 90 years old.

# f-Strings
f-Strings (formatted string literals) provide a way to embed expressions inside string literals, using curly braces {}. This is useful for combining strings and variables, especially when dealing with complex datasets or multiple variables.

# Life in Weeks Program
This program uses maths and f-strings to tell us how many weeks we have left if we live until 90 years old. It takes the current age as input and outputs a message with the time left in weeks.

# Get the current age from the user
age = input("Enter your current age: ")

# Calculate the number of years, weeks left until age 90
years_left = 90 - int(age)
weeks_left = years_left * 52

# Print the result using an f-string
print(f"You have {weeks_left} weeks left.")
Output
For a user input age of 25:
 You have 3380 weeks left.
# Usage
To run the programs, you can use Replit or your local development environment:

Using Replit
Open Replit and create a new Python project.
Copy and paste the code into the Replit editor.
Click the "Run" button to execute the code.

# Contribution
Contributions are welcome! If you have any suggestions for improvements or additional programs to add, feel free to fork the repository, make your changes, and submit a pull request.
