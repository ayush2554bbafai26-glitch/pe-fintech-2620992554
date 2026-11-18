# Lab 3: Chain-of-Thought Prompting

## Objective
Use step-by-step prompting to analyse a fictional lending decision and independently verify the AI's calculations.

## Case: KhataPe
KhataPe has ₹50 crore available to lend.

- Option A: Personal loans at 22% interest, 6% expected default and 2% processing fee.
- Option B: Small-business loans at 18% interest, 3% expected default and 1% processing fee.
- Cost of funds: 10% for both options.
- Operating costs and taxes are ignored.

## Tasks
1. Compare a direct AI answer with a step-by-step answer.
2. Change Option B's expected default rate to 7% and recalculate.
3. Identify three non-financial factors and label facts to verify and hypotheses.

## Verification
Independently calculate interest income, processing fee income, expected loss, cost of funds and net result.

## Files
Task prompts, AI responses, calculation spreadsheet, error-checking table and reflection will be included in this folder.

Lab 3 – 100-Word Reflection

Step-by-step prompting made the AI's answer more transparent and easier to verify, but it did not automatically make it more accurate. In the direct prompt, the AI recommended Option B because of its lower default rate. After using a step-by-step prompt, it calculated the interest income, processing fee, expected loss and cost of funds, and recommended Option A. When Option B's default rate increased to 7%, the AI correctly updated its expected loss and net result. My independent calculations matched the AI's results under the stated assumptions. This exercise taught me that detailed reasoning can be convincing, but independent verification is essential.
