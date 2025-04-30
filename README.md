Business Challenge I – Data Analytics and Engineering
Team 7 | Hult International Business School
Instructor: Prof. Thomas Kurnicki

Overview
This project presents an end-to-end data analysis and engineering initiative focused on the portfolio performance of Point72 Asset Management. Using SQL, Python, and financial analytics, we designed and implemented a relational database system and conducted advanced quantitative assessments to support investment decision-making.

The project analyzes over 1,000 U.S. securities to assess asset allocation, calculate portfolio returns, identify high-performing sectors, and propose strategic reallocations. Our recommendations aim to maximize risk-adjusted returns while supporting compliance and governance standards.

Objectives
Design and implement a normalized MySQL database for portfolio management.

Integrate SQL and Python for querying, visualization, and performance analytics.

Evaluate portfolio returns using discrete and continuous methodologies.

Conduct comparative asset performance analysis against market benchmarks (S&P 500).

Compute risk metrics including beta and Sharpe ratio for over 3,000 securities.

Provide data-driven investment recommendations for portfolio optimization.

Key Results
12-Month Portfolio Return:

Continuous: 27.36%

Discrete: 41.93%

Risk-Adjusted Return (Sharpe Ratio):

Improved from 1.52 to 1.58 after optimization

Top Performing Securities:

Reddit Inc.: +108.73%

Credo Technology: +107.69%

NVIDIA Corp: +77.04%

Underperformers (Proposed for Divestment):

Shell PLC: -11.56%

Canadian National Railways: -16.56%

Database Architecture
Our custom MySQL schema includes the following core entities:

customers, accounts, holdings, products, securities, pricing_daily, research, financial_advisors, compliance

Each table is linked via primary and foreign keys, supporting integrated workflows across client onboarding, product tracking, compliance validation, and investment monitoring.

See: /BCH-7810_Team7_SQL_DDL_Table_Structure.doc for full table schemas.

Technologies Used
Languages: Python, SQL

Libraries: pandas, matplotlib, mysql-connector-python, yfinance

Database: MySQL (Azure-hosted)

Tools: Jupyter Notebook (Google Colab), ER Diagramming, Excel

Notebooks & Analyses
Python Analysis Notebook
Located in: BC1_A2_Pyhton.ipynb

Modules:

Database connection & SQL execution

Portfolio return analysis

Risk factor computation (Beta, Sharpe Ratio)

Asset class allocation

Benchmarking vs. S&P 500

SQL Queries
Found in: BCH-7810_SQL_initial.doc

Queries include:

Portfolio weight computation

Sector-wise return distributions

Monthly asset comparisons

Strategic Recommendations
Based on return dispersion, sector performance, and Sharpe optimization, we recommend:

Divestment from underperforming holdings

Reallocation toward technology and innovation-driven assets

Maintaining liquidity via ETFs to balance aggressive equity exposures

Continued tracking of beta values for customized client risk profiles

Contributors
Team 7

Alexander Neubauer

Abhay Kumar

Bhavana Dasari

Mukul Phogat

Shalini James Paulraj

Tetsuya Kanazawa

Supporting Documents
Full Technical Report (PDF)

Database Design & ERD

Python Code and SQL Query Notebook

Presentation Slides & Screenshots
