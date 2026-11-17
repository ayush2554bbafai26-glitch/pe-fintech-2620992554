# Lab 2 – Task 1: Transaction Tagging

## Objective
To classify 12 fictional bank statement transactions using zero-shot and few-shot prompting and compare the results.

## Tool Used
ChatGPT

## Date
18 November 2026

## Part 1: Zero-Shot Classification

### Prompt V1

Create 12 fictional bank statement transactions for a fintech assignment.

Classify each transaction into exactly one category: Food, Rent, Travel, Shopping, Bills, or Other.

First, use a zero-shot approach without examples. Show the results in a table with Transaction No., Description, and Category.

Use these 12 fictional transactions:
1. Monthly payment to Green Leaf Restaurant – ₹450
2. House rent paid to landlord – ₹12,000
3. Metro card recharge – ₹500
4. Grocery purchase at Fresh Mart – ₹1,250
5. Electricity bill payment – ₹1,800
6. Movie ticket purchase – ₹600
7. Monthly bus pass – ₹900
8. Mobile recharge – ₹299
9. Payment at City Book Store – ₹750
10. Monthly apartment rent – ₹10,000
11. Transfer to a friend for birthday gift – ₹1,000
12. Hospital consultation payment – ₹800

Do not invent any additional transactions.

### Output V1

| Transaction No. | Description | Category |
|---|---|---|
| 1 | Green Leaf Restaurant – ₹450 | Food |
| 2 | House rent – ₹12,000 | Rent |
| 3 | Metro card recharge – ₹500 | Travel |
| 4 | Fresh Mart groceries – ₹1,250 | Food |
| 5 | Electricity bill – ₹1,800 | Bills |
| 6 | Movie ticket – ₹600 | Other |
| 7 | Monthly bus pass – ₹900 | Travel |
| 8 | Mobile recharge – ₹299 | Bills |
| 9 | City Book Store – ₹750 | Shopping |
| 10 | Monthly apartment rent – ₹10,000 | Rent |
| 11 | Birthday gift transfer – ₹1,000 | Other |
| 12 | Hospital consultation – ₹800 | Other |

### Output Summary

All 12 fictional transactions were classified into one of the six predefined categories using zero-shot prompting. No additional transactions were added.

## Part 2: Few-Shot Classification

### Prompt V2

Classify the same 12 bank statement transactions into Food, Rent, Travel, Shopping, Bills, or Other.

First study these 3 examples:

1. Restaurant payment – Food
2. Monthly house rent – Rent
3. Bus ticket – Travel

Now classify all 12 transactions from my previous prompt using these examples as guidance.

Show a table with Transaction No., Description, and Category. Do not add or remove transactions.

### Output V2

| Transaction No. | Description | Category |
|---|---|---|
| 1 | Green Leaf Restaurant – ₹450 | Food |
| 2 | House rent – ₹12,000 | Rent |
| 3 | Metro card recharge – ₹500 | Travel |
| 4 | Fresh Mart groceries – ₹1,250 | Food |
| 5 | Electricity bill – ₹1,800 | Bills |
| 6 | Movie ticket – ₹600 | Other |
| 7 | Monthly bus pass – ₹900 | Travel |
| 8 | Mobile recharge – ₹299 | Bills |
| 9 | City Book Store – ₹750 | Shopping |
| 10 | Monthly apartment rent – ₹10,000 | Rent |
| 11 | Birthday gift transfer – ₹1,000 | Other |
| 12 | Hospital consultation – ₹800 | Other |

## Part 3: Accuracy Comparison and Manual Verification

I compared the zero-shot and few-shot results with the transaction descriptions.

| Approach | Correct classifications | Accuracy |
|---|---:|---:|
| Zero-shot | 12/12 | 100% |
| Few-shot | 12/12 | 100% |

All 12 classifications matched my manual category check. Both approaches produced the same categories.

## Verification Note

## Combined Comparison Table

| Line | Zero-shot tag | Few-shot tag | Correct tag |
|---|---|---|---|
| 1 | Food | Food | Food |
| 2 | Rent | Rent | Rent |
| 3 | Travel | Travel | Travel |
| 4 | Food | Food | Food |
| 5 | Bills | Bills | Bills |
| 6 | Other | Other | Other |
| 7 | Travel | Travel | Travel |
| 8 | Bills | Bills | Bills |
| 9 | Shopping | Shopping | Shopping |
| 10 | Rent | Rent | Rent |
| 11 | Other | Other | Other |
| 12 | Other | Other | Other |

Few-shot prompting used three examples to guide the AI. In this task, it did not improve accuracy because zero-shot prompting had already classified all 12 transactions correctly.
