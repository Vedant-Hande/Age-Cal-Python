
# Age Calculator

A simple Python program that calculates a person's age in years, months, and days based on their inputted age and the current date. The program takes into account leap years and provides user-friendly input validation.

## Features

- Calculates age in years, months, and days.
- Accounts for leap years.
- Validates user input for age to ensure it is a positive integer.

## How It Works

1. **Input**: The program prompts the user for their name and age.
2. **Leap Year Check**: It checks if the years are leap years using the `isleap` function from the `calendar` module.
3. **Days Calculation**: It calculates the total number of days from the year of birth to the current date by:
   - Looping through each year to add either 365 or 366 days.
   - Adding the number of days in the months leading up to the current month.
   - Including the current day.
4. **Output**: The program outputs the user's age in years, months, and days.

## Requirements

- Python 3.x

## Usage

1. Clone the repository:

- git clone https://github.com/Vedant-Hande/Age-Cal-Python.git

2. Navigate to the project directory:

- cd age-calculator

3. Run the program:

- python age_calculator.py
- Follow the prompts to enter your name and age.
 -  Input your name: John
 -  Input your age: 25
   OUTPUT IS _ John's age is 25 years or 300 months or 9,126 days.


## Contributing

Feel free to submit issues or pull requests if you want to contribute to this project!


