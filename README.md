

# Kiva Loan Repayment Analysis

## Overview
This project aims to analyze the loan repayment performance of Kiva, a non-profit organization that facilitates microfinance loans to financially excluded individuals and communities worldwide. By examining the Loan Repayment Rate (LRR) and related metrics, the goal is to gain insights into the effectiveness of Kiva's lending practices and identify areas for improvement.

## Data
The analysis utilizes the Kiva dataset, version 5, containing information on over 670,000 loans disbursed across various countries, sectors, and borrower demographics. The dataset includes features such as loan amount, funded amount, borrower gender, repayment interval, and repayment status.

## Metrics
### 1. Loan Repayment Rate (LRR)
- Definition: The percentage of loan principal and interest repaid by borrowers compared to the total amount disbursed.
- Importance: Critical for assessing portfolio performance, risk management, and social impact.
- Calculation: LRR=( TotalAmountDisbursed / TotalAmountRepaid ) × 100

### 2. Proportion of Paid Loans
- Definition: The proportion of loans that have been fully repaid.
- Importance: Provides a simple measure of loan repayment success.
- Calculation: LRR=(TotalAmountDisbursedforFullyRepaidLoans / TotalAmountRepaidforFullyRepaidLoans) × 100

## Analysis
- Conducted detailed analysis on LRR using two calculation methods.
- Explored repayment rate variations by country, sector, borrower gender, and repayment interval.
- Provided recommendations for improving data quality, conducting segment-specific analysis, and continuous monitoring.

## Files
- **analysis.ipynb**: Jupyter Notebook containing the Python code for data analysis.
- **data.csv**: Kiva dataset used for analysis.
- **README.md**: This file, providing an overview of the project.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/nithishsingh/kiva-loan-repayment-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd kiva-loan-repayment-analysis
   ```

3. Open and run the Jupyter Notebook `case_analysis.ipynb` to view the analysis and results.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn
```

## Contributors
- Nithish Singh (@nithishsingh)


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
Feel free to customize the README.md file according to your project specifics and requirements.
