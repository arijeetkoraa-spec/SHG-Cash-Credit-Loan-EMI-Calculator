## Key Formulas Used in the Calculator

### EMI Calculation
Excel PMT function is used:
=PMT(rate, nper, pv)

This ensures banking-standard EMI calculation.

---

### Outstanding Principal Calculation
Outstanding principal is calculated using the FV function with correct sign conventions:

=-FV(monthly_rate, paid_months, -EMI, principal)

This avoids common errors caused by using EMI × months logic.

---

### Additional Interest for Missed Repayments
Additional interest is calculated using simple interest logic:

Additional Interest = Outstanding Principal × Monthly Rate × Missed Months

---

### Total Loan Balance After Fresh Withdrawal
Total Loan Balance =
Outstanding Principal + Additional Interest + New Loan Amount

The revised EMI is then recalculated on this balance.
