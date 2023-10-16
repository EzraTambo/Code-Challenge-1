# Speed Checker

This project is a simple speed checker that determines whether a driver is speeding, and if so, by how many points.

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- Node.js

### Installation

1. Clone the repository:https://github.com/EzraTambo/Code-Challenge-1.git 


​
git clone 
​


2. Change to the project directory: 


​
cd Code-Challenge-1
​


3. Install the required dependencies:


​
npm install
​


4. Start the development server:


​
npm start
​


Now, you can access the project at https://github.com/EzraTambo/Code-Challenge-1
 in your web browser.

## Usage

To use the speed checker, simply call the checkSpeed function with the speed as the argument:


console.log(checkSpeed(enteredSpeed));
​


The function will return a string indicating whether the driver is within the speed limit, has accumulated points, or if their license has been suspended.

## Contributing

We welcome contributions to the project! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request to the main repository.




# Grade Generator 

Grade Generator is a simple JavaScript function that takes a numeric grade as input and returns a letter grade based on the grade range.

## Installation

You can use this function in your JavaScript project by simply copying and pasting the code into your project.

## Usage

To use the function, call it with the numeric grade as the argument:


javascript
console.log(gradeGenerator(enteredGrade))
​


Replace enteredGrade with the numeric grade you want to convert to a letter grade.

## Examples

Here are some examples of how you can use the function:



console.log(gradeGenerator(85)) // Output: "B"
console.log(gradeGenerator(90)) // Output: "A"


# Salary Calculator

Salary Calculator is a simple JavaScript program that calculates the gross salary, payee, NHIF deductions, NSSF deductions, and net salary of an employee.

## Installation

You can use this program in your JavaScript project by simply copying and pasting the code into your project.

## Usage

To use the program, call the functions with the required arguments:



console.log(calculatePayee(taxableIncome))
console.log(calculateNHIFDeductions(salary))
console.log(calculateNSSFDeductions(salary))
console.log(calculateGrossSalary(basicSalary, benefits))
console.log(calculateNetSalary(grossSalary, payee, NHIFDeductions, NSSFDeductions))
​


Replace the arguments with the appropriate values.

## Examples

Here are some examples of how you can use the functions:


console.log(calculatePayee(85000)) // Output: 24750

You can access all this projects in my github account: https://github.com/EzraTambo