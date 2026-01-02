📊 SHG Cash Credit Loan EMI Calculator (Excel)
🔍 Project Overview

This project is an Excel-based SHG Cash Credit Loan Calculator designed to solve a real-world banking problem faced daily in rural and SHG-focused banking.

In practice, Self Help Group (SHG) loans are:

Sanctioned like Cash Credit (CC)

Repaid in an EMI-based structure

An SHG typically consists of 10 or more members, and each member may:

Withdraw different amounts at different times

Repay EMIs irregularly

Miss some repayments

Withdraw again from the same loan limit

This creates complexity in calculating:

Outstanding principal

Additional interest for missed months

Revised EMI after fresh withdrawals

This Excel tool is built to address exactly that.

🎯 Problem Statement

Traditional EMI calculators do not work for SHG loans because:

Withdrawals are non-uniform

Repayments are irregular

Outstanding principal changes dynamically

Bankers often need to do manual calculations, which are time-consuming and error-prone.

This project simplifies that process using Excel financial functions.

🛠️ Features

EMI calculation using Excel PMT()

Outstanding principal calculation using FV()

Handles missed repayments and penalty interest

Supports cascading / re-borrowing logic

Recalculates EMI after fresh loan withdrawal

Designed from a banker’s workflow perspective

📐 Key Excel Functions Used

PMT() – EMI calculation

FV() – Outstanding principal calculation

Logical handling of paid vs missed months

Proper cash-flow sign conventions

🧠 Business Logic Highlights

Only actually paid EMIs are considered for repayment tracking

Additional interest is calculated on outstanding principal for missed months

New loan amount is added to the existing balance before EMI recalculation

Ensures transparency and explainability at branch level
