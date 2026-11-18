# Lab 3 – Task 2: Break the Reasoning – Changed Assumption

## Objective

To check whether AI updates its calculations correctly when one assumption changes.

## Original Case

KhataPe has ₹50 crore available to lend.

- Option A: Personal loans at 22% interest, 6% expected default and 2% processing fee.
- Option B: Small-business loans at 18% interest, 3% expected default and 1% processing fee.
- Cost of funds: 10% for both options.
- Operating costs and taxes are ignored.

## Changed Assumption

Option B's expected default rate increases from 3% to 7%.

All other assumptions remain unchanged.

## Prompt Used

Recalculate KhataPe's lending decision with exactly one changed assumption.

Option B's expected default rate increases from 3% to 7%.

Keep all other assumptions unchanged:
Loan amount: ₹50 crore.
Option A: 22% interest, 6% default, 2% processing fee.
Option B: 18% interest, 7% default, 1% processing fee.
Cost of funds: 10% for both.

Recalculate interest income, processing fee income, expected loss, cost of funds and net result for both options.

Compare the revised Option B result with its original result and explain whether the recommendation changes.

## Actual AI Response – Recorded Results

The AI kept all assumptions unchanged except Option B's expected default rate.

### Option A – Personal Loans

- Interest income = ₹50 crore × 22% = ₹11 crore
- Processing fee income = ₹50 crore × 2% = ₹1 crore
- Expected default loss = ₹50 crore × 6% = ₹3 crore
- Cost of funds = ₹50 crore × 10% = ₹5 crore
- Net result = ₹11 + ₹1 − ₹3 − ₹5 = **₹4 crore**

### Option B – Small-Business Loans (Revised)

- Interest income = ₹50 crore × 18% = ₹9 crore
- Processing fee income = ₹50 crore × 1% = ₹0.50 crore
- Expected default loss = ₹50 crore × 7% = ₹3.50 crore
- Cost of funds = ₹50 crore × 10% = ₹5 crore
- Net result = ₹9 + ₹0.50 − ₹3.50 − ₹5 = **₹1 crore**

## Comparison of Original and Revised Option B

| Particulars | Original Option B (3% default) | Revised Option B (7% default) |
|---|---:|---:|
| Interest income | ₹9 crore | ₹9 crore |
| Processing fee income | ₹0.50 crore | ₹0.50 crore |
| Expected default loss | ₹1.50 crore | ₹3.50 crore |
| Cost of funds | ₹5 crore | ₹5 crore |
| **Net result** | **₹3 crore** | **₹1 crore** |

## Independent Calculation and Error Check

| Step | AI Result | My Calculation | Correct? | Note |
|---|---:|---:|---|---|
| Option A interest income | ₹11 crore | ₹11 crore | Yes | 50 × 22% |
| Option A processing fee | ₹1 crore | ₹1 crore | Yes | 50 × 2% |
| Option A default loss | ₹3 crore | ₹3 crore | Yes | 50 × 6% |
| Option A cost of funds | ₹5 crore | ₹5 crore | Yes | 50 × 10% |
| Option A net result | ₹4 crore | ₹4 crore | Yes | 11 + 1 − 3 − 5 |
| Option B interest income | ₹9 crore | ₹9 crore | Yes | 50 × 18% |
| Option B processing fee | ₹0.50 crore | ₹0.50 crore | Yes | 50 × 1% |
| Option B revised default loss | ₹3.50 crore | ₹3.50 crore | Yes | 50 × 7% |
| Option B cost of funds | ₹5 crore | ₹5 crore | Yes | 50 × 10% |
| Option B revised net result | ₹1 crore | ₹1 crore | Yes | 9 + 0.50 − 3.50 − 5 |

## Observation

The AI correctly updated Option B's expected default loss from ₹1.50 crore to ₹3.50 crore. Its net result decreased from ₹3 crore to ₹1 crore.

The other figures remained unchanged because their assumptions did not change. The AI also correctly kept Option A's net result at ₹4 crore.

## Final Recommendation

The recommendation does not change. Option A remains the better option under this simplified financial calculation.

Option A gives a net result of ₹4 crore, while revised Option B gives ₹1 crore. The difference is ₹3 crore.

## Conclusion

The AI updated the calculations correctly when the default rate changed. However, checking every calculation independently was important because even a detailed AI response should not be trusted without verification.

**Note:** This is a simplified one-year comparison based on the stated assumptions. Operating costs, taxes and other real-world lending factors are excluded.
