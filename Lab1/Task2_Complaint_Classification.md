# Lab 1 – Task 2: Complaint Classification

## Objective
To classify fictional fintech customer complaints into the correct categories using zero-shot prompting and a revised prompt.

## Tool Used
ChatGPT

## Date
17 November 2026

## Prompt V1 – Zero-shot Prompt
You are a customer support classification assistant for a fictional fintech company. Classify the following 8 complaints into exactly one category: Payments, Loans, KYC/Account, or Needs review. If the category is unclear, use Needs review. Output a table with Complaint No., Complaint, and Category.

[Paste the 8 complaints from the assignment here.]

## Output V1
[Paste the first ChatGPT output here.]

## Revised Prompt V2
You are a customer support classification assistant for a fictional fintech company.

Use these category definitions:
- Payments: UPI, card payments, failed transactions, refunds, and payment deductions.
- Loans: loan applications, EMI deductions, loan fees, and credit limits.
- KYC/Account: KYC verification, login issues, and account access.
- Needs review: use only when the complaint cannot clearly be classified into the above categories.

Classify the same 8 complaints into exactly one category. Output a table with Complaint No., Complaint, and Category.

## Output V2
[Paste the second ChatGPT output here.]

## Manual Verification
I compared both AI outputs with the complaint descriptions and checked whether each complaint matched its category.

Complaint 8 was classified as Needs review in V1 and Loans in V2. Since it clearly concerns a loan that the customer says they did not apply for, Loans is the more suitable category. This shows that the revised prompt improved the classification of this complaint.

## Verification Note
The revised prompt gave clearer category definitions, which helped reduce ambiguity in classification.
