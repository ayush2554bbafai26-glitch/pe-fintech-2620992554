Lab 1 – Task 1: EMI Calculation

Objective

To use zero-shot prompting to explain and calculate the EMI of a loan.

Loan Details

- Loan Amount: ₹2,50,000
- Annual Interest Rate: 14%
- Loan Tenure: 24 months


Tool Used: ChatGPT
Date: 17 November 2026

Prompt – Version 1

Explain EMI to a first-year BBA FinTech student in 50 words.

Output – Version 1

EMI (Equated Monthly Instalment) is a fixed amount paid every month to repay a loan. It includes both the principal amount (borrowed money) and interest (cost of borrowing). EMI is commonly used for home loans, car loans, and personal loans. It helps borrowers repay large amounts in smaller, manageable monthly payments.


Output Summary – Version 1

The AI explained EMI as a fixed monthly loan payment consisting of principal and interest. It also mentioned common loan types and how EMI makes repayment manageable.

Prompt – Version 2 (Revised)

Act as a beginner-friendly finance tutor. Calculate the EMI for a loan of ₹2,50,000 at 14% annual interest for 24 months. First convert the annual interest rate into a monthly rate. Then show the EMI formula, explain each variable, calculate the monthly EMI, total repayment and total interest. Present the answer in a clear table and explain the calculation in simple language.



Output – Version 2

EMI Calculation

Question: Calculate the EMI for a loan of ₹2,50,000 at 14% annual interest for 24 months.

1. Given Information

- Loan Amount (P) = ₹2,50,000
- Annual Interest Rate = 14%
- Loan Tenure (n) = 24 months

2. Convert Annual Interest Rate into Monthly Interest Rate

Formula:

Monthly Interest Rate = Annual Interest Rate ÷ 12 ÷ 100

= 14 ÷ 12 ÷ 100

= 0.0116666667

Therefore, Monthly Interest Rate = 1.16666667%.

3. EMI Formula

EMI = [P × r × (1+r)^n] / [(1+r)^n − 1]

Where:

- P = Principal Loan Amount
- r = Monthly Interest Rate
- n = Number of Monthly Instalments
- EMI = Equated Monthly Instalment

4. Calculation of EMI

Putting the values into the formula:

EMI = [250000 × 0.0116666667 × (1.0116666667)^24] / [(1.0116666667)^24 − 1]

Monthly EMI = ₹12,003.22 (approximately)

5. Calculate Total Repayment

Formula:

Total Repayment = EMI × Number of Months

= 12,003.22 × 24

= ₹2,88,077.30 (approximately)

6. Calculate Total Interest

Formula:

Total Interest = Total Repayment − Principal Loan Amount

= 2,88,077.30 − 2,50,000

= ₹38,077.30 (approximately)

7. Final Answer

| Particulars | Amount |
|---|---:|
| Loan Amount | ₹2,50,000 |
| Annual Interest Rate | 14% |
| Monthly Interest Rate | 1.1667% |
| Loan Tenure | 24 Months |
| Monthly EMI | ₹12,003.22 |
| Total Repayment | ₹2,88,077.30 |
| Total Interest | ₹38,077.30 |

Conclusion

The EMI for a loan of ₹2,50,000 at 14% annual interest for 24 months is approximately ₹12,003.22 per month. The total repayment will be approximately ₹2,88,077.30, out of which ₹38,077.30 is the total interest.

Output Summary – Version 2

The AI calculated the monthly EMI, total repayment and total interest. It showed the monthly interest rate conversion, EMI formula, calculation steps and a final summary table.
Reflection

The revised prompt made the biggest difference because it clearly specified the loan amount, interest rate, tenure and required output. It asked the AI to show the formula, explain each variable and present the results in a table. This made the calculation easier to understand and verify. I independently checked the EMI using the full-precision monthly interest rate. I also noticed that rounding the monthly interest rate too early can affect the final result. This showed me that AI-generated financial calculations should always be checked manually.

EMI Formula and Calculation

Monthly Interest Rate (r) = 14 / (12 × 100) = 0.0116666667

Loan Principal (P) = ₹2,50,000

Number of Monthly Instalments (n) = 24

EMI Formula:

EMI = P × r × (1+r)^n / ((1+r)^n - 1)

Where:

P = Loan Principal (₹2,50,000)

r = Monthly Interest Rate (0.0116666667)

n = Number of Monthly Instalments (24)

Substituting the values:

EMI = 250000 × 0.0116666667 × (1.0116666667)^24 / ((1.0116666667)^24 - 1)

Monthly EMI ≈ ₹12,003.22

Total Repayment = EMI × 24

Total Repayment ≈ ₹2,88,077.30

Total Interest = Total Repayment - Loan Amount

Total Interest ≈ ₹38,077.30

Note: Total repayment and total interest are calculated using the unrounded EMI value.

EMI Summary Table

| Particulars | Value |
|---|---:|
| Loan Amount | ₹2,50,000 |
| Annual Interest Rate | 14% |
| Monthly Interest Rate | 1.166667% |
| Loan Tenure | 24 months |
| Monthly EMI | ₹12,003.22 |
| Total Repayment | ₹2,88,077.30 |
| Total Interest | ₹38,077.30 |
Independent Verification

Monthly interest rate = 0.14 / 12 = 0.0116666667 = 1.166667%

Expected monthly EMI ≈ ₹12,003.22

Expected total repayment ≈ ₹2,88,077.30

Expected total interest ≈ ₹38,077.30

AI Output Check

The AI's EMI value is correct when rounded to two decimal places. However, ₹12,003.22 × 24 = ₹2,88,077.28. The total repayment of ₹2,88,077.30 is based on the unrounded EMI value.

Verification Method: EMI was independently calculated using the EMI formula and the result was compared with the AI-generated output.


