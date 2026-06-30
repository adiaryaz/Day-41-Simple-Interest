# Day-41-Simple-Interest
Day 41/100 - Python program to calculate simple interest

# Calculate Simple Interest
A program to compute the mathematical simple interest on a given principal amount over a specific time period at a defined interest rate.

## 📝 Description

This program prompts the user to input three core financial metrics: the principal amount (initial investment or loan), the annual rate of interest, and the time in years. It then calculates the simple interest earned or owed using the standard formula: $Simple\ Interest = \frac{Principal \times Rate \times Time}{100}$.

The logic is encapsulated within a dedicated function `calculate_simple_interest()`. By casting all three user inputs to floating-point numbers (`float()`), the script ensures it can accurately handle both whole numbers and precise decimal values (e.g., a 4.5% interest rate or a 1.5-year time period) without data loss.

---

## 🎯 Problem Statement

### Input:

* **Input 1:** A floating-point number representing the `principal` amount.
* **Input 2:** A floating-point number representing the annual `rate` of interest (as a percentage).
* **Input 3:** A floating-point number representing the `time` in years.

### Output:

* A formatted string stating: "The Simple Interest is: [simple_interest]"

### Rules:

1. The program must accept three numerical inputs from the user.
2. All inputs must be converted to `float` data types to support decimal operations.
3. The program must use a function to process the calculation using the formula `(principal * rate * time) / 100`.
4. The program must return and print the final calculated simple interest.

---

## 💡 Examples

### Example 1 (Standard Whole Numbers)

**Input:**

```
1000
5
2

```

**Output:**

```
The Simple Interest is: 100.0

```

**Explanation:** The formula processes `(1000 * 5 * 2) / 100`. $1000 \times 5 = 5000$. $5000 \times 2 = 10000$. $10000 / 100 = 100.0$.

### Example 2 (Decimal Interest Rate and Time)

**Input:**

```
5000
4.5
1.5

```

**Output:**

```
The Simple Interest is: 337.5

```

**Explanation:** The formula processes `(5000 * 4.5 * 1.5) / 100`. The floating-point logic accurately handles the 4.5% rate and 1.5-year term to calculate exactly 337.5.

### Example 3 (Zero Time)

**Input:**

```
2500
7
0

```

**Output:**

```
The Simple Interest is: 0.0

```

**Explanation:** If the time is 0 years, mathematically no interest has had time to accrue. The calculation correctly results in 0.0.

---

## 🚀 How to Use

1. **Clone this repository** (or save the script)

```bash
git clone https://github.com/adiaryaz/Day-41-Simple-Interest.git
cd simple-interest

```

2. **Run the program**:

```bash
python main.py

```

Enter the principal amount, interest rate, and time period when prompted to see the calculated simple interest printed to the console.
