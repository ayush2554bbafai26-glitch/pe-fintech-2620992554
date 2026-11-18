# Lab 3 – Task 1: Direct Answer vs Chain-of-Thought Prompting

## Objective

To compare a direct AI answer with a step-by-step AI answer for KhataPe's lending decision and check the accuracy of the calculations.

## Case Information

KhataPe has ₹50 crore available to lend.

- **Option A:** Personal loans at 22% interest, 6% expected default rate and 2% processing fee.
- **Option B:** Small-business loans at 18% interest, 3% expected default rate and 1% processing fee.
- **Cost of funds:** 10% for both options.
- Operating costs and taxes are ignored.

---

## 1. Prompt 1 – Direct Answer

### Prompt Used

Which option should KhataPe choose?

KhataPe has ₹50 crore available to lend next quarter.

Option A: Personal loans at 22% interest, 6% expected default, and 2% processing fee.

Option B: Small-business loans at 18% interest, 3% expected default, and 1% processing fee.

Cost of funds is 10% for both options. Ignore operating costs and taxes.

Give a direct recommendation without detailed calculations.

### Actual AI Response

KhataPe should choose Option B – Small-Business Loans because it has a lower expected default rate of 3%, compared to 6% for personal loans. Although the interest rate is lower, Option B offers lower credit risk and a more stable lending portfolio.

### Observation

The AI recommended Option B because it has a lower expected default rate. It did not calculate the expected financial result, as the prompt asked for a direct recommendation without detailed calculations.

---

## 2. Prompt 2 – Step-by-Step Answer

### Prompt Used

For KhataPe's ₹50 crore lending decision, compare both options step by step.

Option A: Personal loans at 22% interest, 6% expected default, and 2% processing fee.

Option B: Small-business loans at 18% interest, 3% expected default, and 1% processing fee.

Cost of funds is 10% for both. Ignore operating costs and taxes.

Calculate for each option:
1. Interest income
2. Processing fee income
3. Expected default loss
4. Cost of funds
5. Net result

Show the formula and calculation for each step. State your assumptions and compare both options.

### Actual AI Response – Recorded Results

The AI stated these assumptions:

1. The entire ₹50 crore is lent under each option.
2. Interest income is calculated on the full loan amount for one year.
3. Processing fees are calculated as a percentage of the loan amount.
4. Expected default loss is calculated on the full loan amount.
5. Cost of funds is 10% per year.
6. Operating costs and taxes are ignored.

**Option A – Personal Loans**

- Interest income = ₹50 crore × 22% = ₹11 crore
- Processing fee income = ₹50 crore × 2% = ₹1 crore
- Expected default loss = ₹50 crore × 6% = ₹3 crore
- Cost of funds = ₹50 crore × 10% = ₹5 crore
- Net result = ₹11 + ₹1 − ₹3 − ₹5 = **₹4 crore**

**Option B – Small-Business Loans**

- Interest income = ₹50 crore × 18% = ₹9 crore
- Processing fee income = ₹50 crore × 1% = ₹0.50 crore
- Expected default loss = ₹50 crore × 3% = ₹1.50 crore
- Cost of funds = ₹50 crore × 10% = ₹5 crore
- Net result = ₹9 + ₹0.50 − ₹1.50 − ₹5 = **₹3 crore**

### Comparison

| Particulars | Option A | Option B |
|---|---:|---:|
| Loan amount | ₹50 crore | ₹50 crore |
| Interest income | ₹11 crore | ₹9 crore |
| Processing fee income | ₹1 crore | ₹0.50 crore |
| Expected default loss | ₹3 crore | ₹1.50 crore |
| Cost of funds | ₹5 crore | ₹5 crore |
| **Net result** | **₹4 crore** | **₹3 crore** |

**AI's recommendation:** Option A – Personal Loans, because it generates ₹1 crore more expected net income under the stated assumptions.

### Independent Calculation Check

I independently checked each calculation using:

Net Result = Interest Income + Processing Fee Income − Expected Default Loss − Cost of Funds

All the calculations in the AI response are correct under the stated assumptions.

### Observation

The direct prompt recommended Option B based on its lower default risk, whereas the step-by-step prompt recommended Option A based on its higher calculated net result. The detailed response made the calculations easier to verify.

---

## 3. Overall Comparison

| Point | Direct Prompt | Step-by-Step Prompt |
|---|---|---|
| Recommendation | Option B | Option A |
| Main reason | Lower default risk | Higher expected net result |
| Detailed calculations | Not provided | Provided |
| Easy to verify calculations | No | Yes |

### Conclusion

The direct answer focused mainly on credit risk, while the step-by-step answer compared the financial results. Step-by-step prompting made the answer more transparent and easier to check. However, a detailed explanation should not automatically be trusted; its calculations and assumptions must still be verified independently.

**Note:** The one-year period and the calculation of expected default loss on the full loan amount are assumptions used in this simplified comparison. The result is not a complete real-world lending profitability analysis.
