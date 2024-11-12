# Loan Default Risk Analysis

This project is an exploratory data analysis (EDA) case study on Lending Club’s loan dataset. The goal is to identify patterns and insights to predict the likelihood of loan default, supporting informed lending decisions and reducing financial risks.

## Table of Contents
- [General Information](#general-information)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## General Information
Lending Club operates as a peer-to-peer lending platform, and this analysis focuses on understanding the factors influencing loan defaults. The study identifies key risk indicators, helping to improve decision-making and optimize the loan approval process.

### Key Risk Types
1. **High Repayment Likelihood**: Denying credit to likely repayers can result in lost business opportunities.
2. **High Default Likelihood**: Approving loans for likely defaulters may lead to financial loss.

The aim of this analysis is to balance these risks, identifying loans that are less likely to default while capturing business from reliable borrowers.

## Objectives
- **Minimize Financial Loss**: Analyze loan data to uncover trends and indicators of default risk.
- **Optimize Loan Approval**: Derive insights to improve lending criteria and target low-risk borrowers.

## Dataset
The dataset used for this project contains Lending Club loan records, including:
- **Loan details**: Amount, purpose, interest rate, and grade
- **Borrower information**: Annual income, debt-to-income ratio, and verification status
- **Loan status**: Fully paid, charged off (default), and other payment histories

This dataset is publicly available on Lending Club’s platform for educational and analytical use.

## Technologies Used
- **Python**: For data analysis and manipulation
- **Pandas & NumPy**: For data handling and preprocessing
- **Matplotlib & Seaborn**: For data visualization

## Conclusions
The analysis has revealed several important findings:
- **Default Rate**: 14% of loans are charged off, while 86% are fully paid, suggesting areas for improvement in default prediction.
- **Small Business Loans**: Small business loans have a high default rate, indicating that stricter criteria may reduce risk.
- **Verification Status**: Surprisingly, verified customers show a higher default rate than non-verified ones, warranting further examination.
- **Yearly Trends**: Default rates peaked in 2007, decreased until 2009, and have been rising steadily since 2010.
- **Interest Rate**: Loans with higher interest rates show a greater tendency to default, highlighting interest rate as a significant risk factor.

## Acknowledgements
Special thanks to:
- [GeeksForGeeks](https://www.geeksforgeeks.org/) for technical resources
- [TutorialsPoint](https://www.tutorialspoint.com/) for reference materials
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html) for visualization guidance

## Contact
Created by [@scpowar](https://github.com/scpowar) - feel free to reach out for questions or collaboration!
