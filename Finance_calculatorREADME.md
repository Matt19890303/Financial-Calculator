# Finance calculator 

This program allows the user to calculate their interest on an investment or calculate 
the amount that should be repaid on a home loan each month.

## Task

Build a calculator that can output a result based on the clients choices for Simple/Compound interest rates for an investment
and also the interest rate for a bond 

## Run Locally
 - Run this command git clone https://github.com/Matt19890303/Financial-Calculator/.git
 - I used Pycharm and imported the math module ('import math')
 - You can run the calculator and play around

## Usage

```python
import math

# returns Simple interest total
deposit_amount * (1 + (interest_rate / 100) * years_investing) = Simple investment 
500 * (1 + (8 / 100) * 5) = 700.00

# returns Compound interest total
deposit_amount * math.pow((1 + (interest_rate / 100)), years_investing) = Compound investment
500 * math.pow(1 + (8 / 100), 5) = 734.66

# returns home loan repayment
house_value * (interest_rate * (1 + interest_rate) ** num_months) / ((1 + interest_rate) ** num_months - 1) = repayment
1500000 * (7 * (1 + 7) ** 48) / ((1 + 7) ** 48 - 1) = 35919.37

```