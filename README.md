# Will the Customer Accept the Coupon

## Overview
The goal of this project is to use visualizations and probability distributions to distinguish between customers 
who accepted a driving coupon versus those who did not.

## Data 
The dataset (`coupons.csv`) includes driver demographics, travel context, and coupon acceptance
information.
- Gender: male, female
- Age: below 21, 21 to 25, 26 to 30, etc.
- Marital Status: single, married partner, unmarried partner, or widowed
- Number of children: 0, 1, or more than 1
- Education: high school, bachelors degree, associates degree, or graduate degree
- Occupation: architecture & engineering, business & financial, etc.
- Annual income: less than $12500, $12500 - $24999, $25000 - $37499, etc.
- Driving destination: home, work, or no urgent destination
- Location of user
- Weather: sunny, rainy, or snowy
- Temperature: 30F, 55F, or 80F
- Time: 10AM, 2PM, or 6PM
- Passenger: alone, partner, kid(s), or friend(s)

## Data Cleaning Steps
- Dropped columns with >90% missing values (e.g., `car`).
- Replaced missing values for categorical and numeric columns.
- Removed duplicate rows.

   
## Key findings
- Drivers who visit bars more than once a month accept bar coupons
- Drivers without kids had higher acceptance rates.
- Younger and unmarried drivers accept bar coupons
- work in professional and not in farming, fishing, or forestry has higher acceptance rate.
- Low-income who earnunder $50K and dine out frequently found to use bar coupons more.

## Tech Stack
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook for data analysis

## Author
■ umavsree@gmail.com
■ [GitHub Profile](https://github.com/umavsree)
