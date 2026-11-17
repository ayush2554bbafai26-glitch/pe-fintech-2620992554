# Lab 1 – Task 2: Complaint Classification

## Objective
To classify 8 fictional fintech customer complaints into Payments, Loans, KYC/Account, or Needs review using zero-shot prompting and a revised prompt.

## Tool Used
ChatGPT

## Date
17 November 2026

## Prompt V1 – Zero-shot Prompt

You are a customer support classification assistant for a fictional fintech company. Classify the following 8 complaints into exactly one category: Payments, Loans, KYC/Account, or Needs review. If the category is unclear, use Needs review. Output a table with Complaint No., Complaint, and Category.

1. UPI payment failed but amount debited.
2. EMI deducted twice.
3. KYC rejected despite clear PAN copy.
4. Loan app charged a fee I was not told about.
5. Cannot log in after changing my phone number.
6. Refund for failed card payment not received after 10 days.
7. Credit limit reduced without notice.
8. App shows loan never applied for.

## Output V1

| Complaint No. | Complaint | Category |
|---|---|---|
| 1 | UPI payment failed but amount debited. | Payments |
| 2 | EMI deducted twice. | Loans |
| 3 | KYC rejected despite clear PAN copy. | KYC/Account |
| 4 | Loan app charged a fee I was not told about. | Loans |
| 5 | Cannot log in after changing my phone number. | KYC/Account |
| 6 | Refund for failed card payment not received after 10 days. | Payments |
| 7 | Credit limit reduced without notice. | Loans |
| 8 | App shows loan never applied for. | Needs review |

## Revised Prompt V2

You are a customer support classification assistant for a fictional fintech company.

Use these category definitions:
- Payments: UPI, card payments, failed transactions, refunds, and payment deductions.
- Loans: loan applications, EMI deductions, loan fees, and credit limits.
- KYC/Account: KYC verification, login issues, and account access.
- Needs review: use when the complaint cannot clearly be classified into the above categories.

Classify the same 8 complaints into exactly one category. Output a table with Complaint No., Complaint, and Category.

## Output V2

| Complaint No. | Complaint | Category |
|---|---|---|
| 1 | UPI payment failed but amount debited. | Payments |
| 2 | EMI deducted twice. | Loans |
| 3 | KYC rejected despite clear PAN copy. | KYC/Account |
| 4 | Loan app charged a fee I was not told about. | Loans |
| 5 | Cannot log in after changing my phone number. | KYC/Account |
| 6 | Refund for failed card payment not received after 10 days. | Payments |
| 7 | Credit limit reduced without notice. | Loans |
| 8 | App shows loan never applied for. | Loans |

## Manual Verification

I manually checked all 8 classifications. Complaints 1 to 7 received the same categories in both outputs. Complaint 8 changed from Needs review in V1 to Loans in V2.

I consider Loans the more suitable category for Complaint 8 because the complaint is specifically about a loan appearing in the app without the customer's application. The revised prompt's category definitions helped make the classification clearer.

## Verification Note

The revised prompt improved clarity by defining each category before classification. I compared both outputs and checked the category assigned to every complaint.
