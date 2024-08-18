# Portfolio Optimization Project

## Overview
This project is a practical implementation of portfolio optimization techniques. The project involves applying various optimization methods to real-world financial data from the S&P 500 market, focusing on minimizing risk while meeting certain return expectations.

## Project Structure
- **Dataset**: The project uses stock price data for 471 stocks from the S&P 500 market, spanning from 2013 to 2018. The data is split into training (`train.csv`) and testing (`test.csv`) datasets.
- **Jupyter Notebook**: The main code for the project is provided in the `ftec2101_project_2021.ipynb` notebook. This notebook contains code to perform the optimization tasks outlined in the project specification.
- **Helper Functions**: The `reusablefunc.jl` file includes functions that simplify various tasks, such as calculating the Sharpe ratio and handling transaction costs.

## Tasks

### Compulsory Tasks (50%)
1. **Task 1**: Derivation of KKT conditions and analysis of a simple portfolio optimization problem.
2. **Task 2**: Formulation of a mixed-integer nonlinear program (MI-NLP) for portfolio optimization.
3. **Task 3**: Formulation of a second-order cone program (SOCP) for portfolio optimization.

### Computational Implementation
4. **Task 4**: Data preprocessing and initial analysis, including plotting stock returns.
5. **Task 5**: Implementation of the closed-form solution for the simple portfolio optimization problem.
6. **Task 6**: Numerical solution of the MI-NLP and SOCP problems using the provided dataset.

### Performance Evaluation
7. **Task 7**: Comparison of portfolio performance on the testing set using the Sharpe ratio and other metrics.

### Competitive Task (30%)
8. **Task 8**: Development of a custom solver for large-scale portfolio optimization using a projection-based iterative algorithm.

## Requirements
- **Software**: Julia or Python with optimization packages such as JuMP, ECOS, Ipopt, and cvxpy.
- **Data**: The dataset provided in the project files (`ftec_project_files.zip` and `ftec_project_subgroupi.zip`).

