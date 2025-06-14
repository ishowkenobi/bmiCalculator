# BMI Calculator

This Java application is used to calculate the Body Mass Index (BMI). The user can enter their name, age, weight, and height, and the program will calculate their BMI. Afterward, it will display the BMI category based on the calculated value.

## Features
- Takes the user's name, age, weight, and height as input.
- Converts weight to kilograms and height to meters.
- Displays the BMI result and category based on the following criteria:
  - **Underweight**: BMI < 18.5
  - **Normal**: 18.5 ≤ BMI < 25.0
  - **Overweight**: 25.0 ≤ BMI < 30.0
  - **Obese**: BMI ≥ 30.0

## Usage

### Prerequisites

To run this application, you need to have [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk15-downloads.html) installed on your computer. You also need an IDE like Eclipse or any other Java development environment.

### Steps:

1. **Clone the Project:**
   Clone the GitHub repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/bmi-calculator.git
Example Input and Output
Enter name, age, weight, height: (as comma separated) cemal, 23, 77, 180
** The BMI result for cemal ( Age: 23 Weight: 77.0 Height: 180.0) is Normal
Project Structure
bmi-calculator/
├── Bmi.java         # BMI calculation class
├── BmiTest.java     # Main class for user input and displaying results
└── README.md        # Information about the project
