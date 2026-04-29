Simple Linear Regression — Interactive ML Lab

A browser-based interactive lab to learn and experiment with Simple Linear Regression (SLR).
This project demonstrates how a regression model is built step-by-step, with real-time visualization and predictions.

Overview

This application helps users understand the fundamentals of linear regression by:

Explaining core concepts and formulas
Walking through calculations step-by-step
Visualizing data points and regression line
Allowing custom dataset experimentation

It is designed for students and beginners in machine learning.

Features
1. Concept Explanation
Definition of Simple Linear Regression

Mathematical model:

ŷ = β₀ + β₁x
Key parameters:
Intercept (β₀)
Slope (β₁)
SSE, MSE, RMSE
R² score
Pearson correlation coefficient
2. Step-by-Step Algorithm Execution

The lab breaks down regression into clear steps:

Load dataset
Compute mean values
Calculate deviations
Compute slope (β₁)
Compute intercept (β₀)
Build final regression model
3. Interactive Lab
Input custom X and Y values (comma-separated)
Built-in dataset presets:
Study Hours vs Score
Experience vs Salary
House Area vs Price
Temperature vs Sales
Step-by-step execution with detailed trace
4. Visualization
Scatter plot of data points
Regression line
Residual lines
Rendered using HTML Canvas
5. Prediction
Enter any X value
Get predicted Y instantly using trained model
6. Learning Support
Embedded video explanation
References for further study
Tech Stack
HTML5
CSS3
Vanilla JavaScript
HTML Canvas API

No external frameworks or libraries are used.

Project Structure
simple-linear-regression-lab/
│
├── index.html      # Complete application (UI + logic)
└── README.md       # Documentation
Getting Started
Run Locally

Clone the repository:

git clone https://github.com/your-username/simple-linear-regression-lab.git

Open the project:

cd simple-linear-regression-lab
Run the file:
Double-click index.html, or
Open it in any modern browser
Usage
Navigate to the Lab section
Enter X and Y values (same number of values)
Click START / NEXT STEP
Follow each step of computation
Use the Predict feature for new inputs
Example

Input:

X: 1, 2, 3, 4, 5
Y: 55, 60, 70, 75, 90

Output:

ŷ = 44.5 + 8.5x
Deployment

You can deploy this project using GitHub Pages:

Go to repository Settings
Open Pages
Select branch: main
Save

Your app will be available at:

https://your-username.github.io/simple-linear-regression-lab/
Future Improvements
Multiple Linear Regression support
Gradient Descent visualization
Export results (CSV/PDF)
Improved mobile responsiveness
Authors
Ch.V.D. Teja
R. Madesh
License

This project is licensed under the MIT License.