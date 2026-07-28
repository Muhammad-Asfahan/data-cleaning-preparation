Data Analytics - Project 2: Exploratory Data Analysis (EDA)

Overview
This project involved performing Exploratory Data Analysis (EDA) on the cleaned e-commerce dataset (output of Project 1) part of the DecodeLabs Data Analytics Internship (2026).
 What was done
- Calculated basic statistics (Mean, Median, Count, Min, Max) for all numeric columns
- Visualized TotalPrice distribution using a Histogram (identified right-skew)
- Detected outliers using the IQR method (1.5x rule) and confirmed via Boxplot
- Analyzed frequency distribution across 5 categorical columns (Product, PaymentMethod, OrderStatus, CouponCode, ReferralSource)
- Performed Pearson Correlation analysis between numeric variables
- Compiled findings into an Executive Summary with actionable recommendations
Key Findings
- TotalPrice distribution is right-skewed (Mean 1053.97 vs Median 823.62)
- 8 genuine high-value outlier orders identified (all max-quantity, high-price bulk orders)
- Printer is the most-ordered product; Phone is the least
- FREESHIP is the most redeemed coupon (622 uses)
- Instagram is the top referral source (259)
- UnitPrice and TotalPrice show strong correlation (0.717); Quantity and UnitPrice are nearly uncorrelated (0.015)
Tools used
Excel formulas: AVERAGE, MEDIAN, COUNT, MIN, MAX, QUARTILE, COUNTIF, CORREL
Charts: Histogram, Box and Whisker Plot

Files
`Decode Data Analytics - EDA.xlsx` — contains Dataset, Change Log, EDA - Basic Stats, and Executive Summary sheets
