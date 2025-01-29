# Banks-portfolio-selection-using-genetic-algorithm
This analysis is to see how Genetic algorithm can help us with more return in our investement and minize the risk to be taken.

## Table of contents 
- 1.[project overview](#project-overview)
- 2.[Data sources](#data-sources) 
- 3.[Tools](#tools)
- 4.[key features](#key-features)
- 5.[key Analysis](#key-analysis)
- 6.[Analysis findings](#analysis-findings)
- 7.[Recommendations](#recommendations)

### project overview
---
The Banks-Portfolio-Selection-Using-Genetic-Algorithm project aims to optimize the selection of Nigerian bank stocks to achieve the highest potential returns while managing risk. This project employs genetic algorithms (GAs), which are inspired by evolutionary processes like natural selection, to efficiently navigate and identify optimal portfolio configurations. By balancing returns and risks, this approach is designed to offer robust and data-driven financial strategies for investors.


![Dashboard](https://github.com/FebeianBELLO/Banks-porfolio-select-using-genetic-algorithm/blob/main/Genetic%20Algorithms...docX.png)

### Data sources 
---
The data used in this project was sourced from ng.investing.com, which provides comprehensive  historical stock prices of five (5) banks, covering daily closing stock prices from 2021 to 2023.
### Tools
---
The tools used in this project were primarily Python-based:

    Pandas: For data import, cleaning, and manipulation.
    NumPy: For numerical calculations, including returns and risk calculations.
    Matplotlib & Seaborn: For data visualization and charting.
    SciPy: For optimization functions.
    DEAP (Distributed Evolutionary Algorithms in Python): To implement the genetic algorithm for portfolio optimization.
    Jupyter Notebook: For interactive data analysis and reporting.
### Methods 
   - Problem Definition: Define the objective of maximizing returns and minimizing risk in a bank portfolio.

   - Data Collection & Preprocessing
   
![Dashboard](https://github.com/FebeianBELLO/Banks-porfolio-select-using-genetic-algorithm/blob/main/line%20chart%201.png)
![Dashboard](https://github.com/FebeianBELLO/Banks-porfolio-select-using-genetic-algorithm/blob/main/bar%20chart%202.png)
  -  Genetic Algorithm Design: Define chromosome representation (weights of stocks),Set initial population of portfolios.

-    Fitness Function: Calculate the Sharpe ratio to evaluate the portfolios' risk-return efficiency.

   - Genetic Operations: Selection,Crossover and Mutation


    - Iterative Evolution: Evolve portfolios over multiple generations, selecting, crossing over, and mutating until convergence.

    - Portfolio Evaluation: Select the portfolio with the highest Sharpe ratio as the optimal solution.

    - Results Interpretation: Analyze the optimal portfolio's return, risk, and Sharpe ratio.

    Comparison with Mean-Variance Portfolio: Compare the GA-optimized portfolio to a mean-variance portfolio for performance assessment.

 
![Dashboard](https://github.com/FebeianBELLO/Banks-porfolio-select-using-genetic-algorithm/blob/main/COMPAER%202.png)
    Conclusion: Summarize the genetic algorithm's effectiveness in optimizing portfolio allocation.

This process is tailored to optimize returns and minimize risk using genetic algorithms, as you did in your study of Nigerian bank stocks.
### key features
---
- Optimizes portfolio allocation by minimizing risk while maximizing return using a genetic algorithm approach.
-Provides risk-return profiles that help investors choose the optimal allocation of bank stocks there by increasing return and reducing loss.
-Compares genetic algorithm-based portfolios with traditional mean-variance optimization methods
-Analyzes financial performance metrics such as risk, return, and Sharpe ratios for each portfolio.
-Enables better decision-making for portfolio managers through data-driven insights.
-Highlights the most efficient portfolio based on a higher Sharpe ratio.
### key Analysis 
---
- Risk-Return Tradeoff: The genetic algorithm generates multiple portfolios with varying risk-return profiles to determine the optimal stock allocation.
-Performance Comparison: The portfolios generated by the genetic algorithm are compared to the mean-variance optimized portfolio to evaluate the effectiveness of each method.
-Portfolio Efficiency: The genetic algorithm helps identify portfolios that deliver high returns relative to the amount of risk undertaken, making them more efficient than traditional methods.
-Sharpe Ratio Optimization: Each portfolio is assessed using the Sharpe ratio, which measures return per unit of risk, identifying which portfolio delivers the best balance of risk and reward.

![Dashboard](https://github.com/FebeianBELLO/Banks-porfolio-select-using-genetic-algorithm/blob/main/Table...png)


### Analysis findings 
---
- Portfolio Performance: Four portfolios were generated by the genetic algorithm with the following results:

    Portfolio 1: Return of 0.0611, Risk of 0.00210, Sharpe Ratio of 1.000.
    Portfolio 2: Return of 0.0630, Risk of 0.0019, Sharpe Ratio of 2.263 (most efficient portfolio).
    Portfolio 3: Return of 0.0623, Risk of 0.0021, Sharpe Ratio of 1.5714.
    Portfolio 4: Return of 0.0611, Risk of 0.002000, Sharpe Ratio of 1.0500.

- Mean-Variance Portfolio: Compared to the genetic algorithm portfolios, the mean-variance portfolio showed inferior performance:

    Return: 0.0507
    Risk: 0.0411
    Sharpe Ratio: -0.2011

- optimal allocation  Portfolio 2 from the genetic algorithm approach was found to be the most efficient, offering the highest return for the lowest level of risk, with a Sharpe ratio of 2.263, significantly outperforming the mean-variance optimized portfolio.
 ![Dashboard](https://github.com/FebeianBELLO/Banks-porfolio-select-using-genetic-algorithm/blob/main/port%20GA1%20%20%204.png)
 ![Dashboard](https://github.com/FebeianBELLO/Banks-porfolio-select-using-genetic-algorithm/blob/main/port%20GA2%20%20%205.png)
  ![Dashboard](https://github.com/FebeianBELLO/Banks-porfolio-select-using-genetic-algorithm/blob/main/port%20GA3%20%20%206.png)
  ![Dashboard](https://github.com/FebeianBELLO/Banks-porfolio-select-using-genetic-algorithm/blob/main/port%20GA4.png)


