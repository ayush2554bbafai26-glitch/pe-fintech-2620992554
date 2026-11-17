Lab 2 – Task 2: Misleading Few-Shot Examples

Objective

To observe how misleading examples affect AI classification.

Tool Used

ChatGPT

Misleading Examples

1. UPI restaurant payment – Food
2. UPI mobile recharge – Food
3. UPI online shopping payment – Food

AI Output

Transaction No.| Description| Category
1| Monthly payment to Green Leaf Restaurant ₹450| Food
2| House rent paid to landlord ₹12,000| Rent
3| Metro card recharge ₹500| Travel
4| Grocery purchase at Fresh Mart ₹1,250| Food
5| Electricity bill payment ₹1,800| Bills
6| Movie ticket purchase ₹600| Other
7| Monthly bus pass ₹900| Travel
8| Mobile recharge ₹299| Food
9| Payment at City Book Store ₹750| Shopping
10| Monthly apartment rent ₹10,000| Rent
11| Transfer to friend for birthday gift ₹1,000| Other
12| Hospital consultation payment ₹800| Other

Observation

In the original few-shot output, mobile recharge was tagged as Bills. After using misleading examples, it was tagged as Food. The other 11 transactions kept the same categories. This shows that AI can follow examples even when they are incorrect. Few-shot prompting depends on the quality of examples. Incorrect examples can confuse the model and reduce accuracy. Therefore, examples should be checked carefully before using them.
