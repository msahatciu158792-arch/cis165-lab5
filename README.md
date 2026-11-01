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
