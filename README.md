# 📊 Life Insurance Premium Pricing Model

## 📌 Project Overview

This project develops an actuarial pricing model in Excel to calculate the Net Single Premium of a term life insurance policy using mortality probabilities and discounted cash flow principles.

The model applies core actuarial concepts including survival probabilities, present value calculations, and sensitivity analysis.

---

## 🎯 Objective

To compute the actuarially fair premium by calculating the Expected Present Value (EPV) of future death benefits.

---

## 📊 Assumptions

- Entry Age: 30 years  
- Policy Term: 30 years  
- Death Benefit: ₹10,00,000  
- Base Interest Rate: 5%  
- Mortality Data: Synthetic age-based mortality rates  

---

## 🧠 Methodology

The pricing model follows standard actuarial steps:

1. Mortality rates (qₓ) defined by age  
2. Survival probabilities calculated as:

   pₓ = 1 − qₓ

3. Cumulative survival probability computed  
4. Annual probability of death derived  
5. Discount factor calculated as:

   v = 1 / (1 + i)

6. Expected Present Value calculated using:

   EPV = Σ (Probability of Death × Benefit × Discount Factor)

The Net Single Premium equals the total EPV of expected death benefits.

---

## ✅ Results

**Net Single Premium (at 5% interest rate):**

₹64,641

---

## 📈 Sensitivity Analysis

| Interest Rate | Net Single Premium |
|---------------|-------------------|
| 3% | ₹94,508 |
| 5% | ₹64,641 |
| 7% | ₹45,605 |
| 9% | ₹33,187 |

### Observation

The premium is inversely related to the interest rate.  
Higher discount rates reduce the present value of expected claims, resulting in lower required premiums.

---

## 📊 Visualizations Included

- Mortality Rate by Age  
- Annual Probability of Death  
- EPV Contribution by Age  
- Premium Sensitivity to Interest Rate  

---

## 🛠 Tools Used

- Microsoft Excel  
- Actuarial Mathematics  
- Probability Theory  
- Financial Discounting  

---

## 🚀 Future Improvements

- Level Annual Premium calculation  
- Expense loading integration  
- Implementation using real mortality tables  
- Python version of the model  

---

## 👤 Author

Basim Nihal  
BSc (Hons) Mathematics  
Aspiring Actuarial Analyst  
