# cis165-lab5
## Program Plans

### Program 1 — Compound Interest

- **Inputs:** Principal balance, annual interest rate, and number of compounding periods.
- **Conversion:** Divide the annual interest percentage by 100 to get a decimal rate.
- **Variables:** principal, annual_rate, rate, times_compounded, amount, and interest_earned.
- **Formula:** Use `pow()` to calculate compound interest and subtract the principal to find the interest earned.
- **Output:** Display the interest rate, compounding periods, principal, interest earned, and final savings amount.
- **Tests:** Use the instructor's assigned values and a second test with different positive values.

### Program 2 — Monthly Loan Payment

- **Inputs:** Loan amount, annual interest rate, and number of monthly payments.
- **Conversion:** Divide the annual percentage rate by 100 and then by 12.
- **Variables:** loan_amount, annual_rate, monthly_rate, number_of_payments, monthly_payment, amount_paid_back, and interest_paid.
- **Formula:** Use `pow()` to calculate the monthly payment, then calculate the total amount paid back and interest paid.
- **Output:** Display the loan amount, monthly rate, number of payments, monthly payment, amount paid back, and interest paid.
- **Tests:** Use the instructor's assigned values and a second test with different positive values.
## Test Results

| Program and test | Inputs | Expected results | Actual results | Match or correction |
|---|---|---|---|---|
| Compound interest — assigned | 1000, 4.25%, 12 | Interest: $43.34; Amount: $1043.34 | Interest: $43.34; Amount: $1043.34 | Match |
| Compound interest — changed | 2000, 5%, 4 | Interest: $101.89; Amount: $2101.89 | Interest: $101.89; Amount: $2101.89 | Match |
| Loan payment — assigned | 10000, 12%, 36 | Payment: $332.14; Total: $11957.15; Interest: $1957.15 | Payment: $332.14; Total: $11957.15; Interest: $1957.15 | Match |
| Loan payment — changed | 5000, 6%, 24 | Payment: $221.60; Total: $5318.47; Interest: $318.47 | Payment: $221.60; Total: $5318.47; Interest: $318.47 | Match |

## Code Explanations

1. **Why must a percentage be divided by 100?**

   A percentage must be divided by 100 because the formulas need a decimal rate instead of a percentage. For example, 12% becomes 0.12.

2. **How does pow represent exponentiation?**

   The pow function raises a number to a power. For example, pow(2, 3) means 2 multiplied by itself three times.

3. **What does the number of compounding periods change?**

   The number of compounding periods determines how often interest is added to the principal during the year. More frequent compounding can increase the amount of interest earned.

4. **How is an annual interest rate converted to a monthly rate?**

   First, divide the annual percentage rate by 100. Then divide the result by 12 to get the monthly decimal rate.

5. **Why should double be used for these calculations?**

   Double is used because financial calculations involve decimal values. It provides more precision than an integer.

6. **Why should calculations use full precision when money is displayed to two decimal places?**

   Using full precision helps prevent rounding errors from adding up during calculations. The program should round only when displaying the final results.

7. **How are the amount paid back and total interest calculated?**

   The amount paid back is calculated by multiplying the monthly payment by the number of payments. Total interest is calculated by subtracting the original loan amount from the amount paid back.

8. **Why are calculations stored in variables before being displayed?**

   Storing calculations in variables makes the program easier to read, understand, test, and correct.
