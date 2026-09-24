# Loan Amortization Calculator

A small React + TypeScript app that takes a loan amount, interest rate, and term and produces a full month-by-month amortization schedule: payment, interest, principal, and remaining balance.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

## How it works

The form state feeds [`loanjs`](https://www.npmjs.com/package/loanjs), which computes equal-installment (annuity) payments over `years × 12` months. The result renders as a currency-formatted table.

## Run locally

```bash
npm install
npm start    # http://localhost:3000
```

## Next steps

- Chart the principal vs. interest split over time (Plotly is already a dependency)
- Validate inputs and support extra-payment scenarios
