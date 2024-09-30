# Restaurant Profit Optimization Project

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Scenarios](#scenarios)
- [Results and Visualizations](#results-and-visualizations)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project aims to optimize the profit of a restaurant using Linear Programming (LP) techniques. The goal is to determine the optimal number of each dish to prepare daily while considering constraints like ingredient availability, chef working hours, and customer demand. The optimization model is implemented using Python's PuLP library.

## Installation
To run this project, you need to have Python installed along with the required libraries. Follow these steps to set up the environment:

1. Clone the repository:
   git clone https://github.com/ayan-11/Optimizing-Technique-Problem.git
   cd restaurant-profit-optimization
2.Install the required libraries:
  pip install pandas numpy pulp matplotlib
  Dataset
  The synthetic dataset generated for this project includes the following columns:
  
  Dish Name: The name of the dish.
  Profit per Dish: The profit earned from selling one unit of the dish.
  Ingredient Usage (units): The amount of each ingredient required per dish.
  Preparation Time (hours): The time it takes to prepare each dish.
  The dataset is saved as restaurant_data_india.csv.

Usage
Run the Jupyter Notebook or Python script to load the dataset and execute the optimization model.
The project includes different scenarios with varying constraints to observe how they impact the optimal dish preparation strategy and total profit.
Scenarios
The project evaluates four scenarios:

Basic Constraints: Runs the optimization with standard ingredient and labor limits.
Minimum Demand Constraints: Adds a minimum demand for specific dishes.
Maximum Production Constraints: Sets maximum limits on how many units of certain dishes can be prepared.
Both Minimum Demand and Maximum Production Constraints: Combines both constraints for a comprehensive analysis.
Results and Visualizations
The results of each scenario are visualized using Matplotlib, showing:

Total profit for each scenario.
Number of dishes to prepare for each dish across different scenarios.
Technologies Used
Python: Programming language used for implementation.
Pandas: Library for data manipulation and analysis.
NumPy: Library for numerical operations.
PuLP: Library for solving linear programming problems.
Matplotlib: Library for creating visualizations.
Contributing
Contributions are welcome! If you have suggestions for improvements or features, please open an issue or submit a pull request.
