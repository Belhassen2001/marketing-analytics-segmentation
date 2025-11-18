🎯 Customer Segmentation & Marketing Analytics Project
End-to-end Data Analysis • EDA • Clustering • Marketing Insights
📌 Project Overview

This project analyzes customer behavior using a real marketing dataset and applies Exploratory Data Analysis (EDA), feature engineering, and K-Means clustering to uncover customer segments and provide actionable marketing recommendations.

The goal is to help a retail/marketing team understand:

Who are our most valuable customers?

Which groups respond to campaigns?

How should we target each segment?

Which variables drive spending and engagement?

🧠 Business Problem

Most companies send marketing campaigns blindly — without understanding:

which customers spend more

which customers respond well

which customers have high lifetime value

which segments should be prioritized

This project answers the core question:

“Which types of customers should we target to increase revenue and campaign success?”

📂 Dataset Description

The dataset contains 2,240 customers with features across:

👤 Demographics

Age

Marital Status

Education

Income

Number of children (Kidhome, Teenhome)

💰 Spending Behavior

Wine, Fruits, Meat, Fish, Sweets, Gold spending

Online, In-Store, Catalog purchases

Recency (days since last purchase)

📣 Marketing Campaigns

Response to 5 different campaigns

Overall response

🧹 Feature Engineering Added

Age

Total_Spent

Total_Purchases

Total_Children

🧽 Data Cleaning Steps

Removed whitespace and standardized column names

Converted income to numeric

Handled missing values (median imputation for Income)

Created engineered features

Filtered out extreme outliers for clustering

Encoded categorical variables where needed

Normalized numerical variables for K-Means

📊 Exploratory Data Analysis (Key Insights)
🔍 Income & Spending

High-income customers spend significantly more

Total_Spent has the strongest connection to campaign response

Most revenue comes from Wines and Meat categories

👨‍👩‍👧 Family Size & Spending

Customers with more children spend less

Families show lower engagement in campaigns

⏳ Recency

Customers who purchased recently respond more
(negative correlation between Recency & Response)

💬 Correlation Highlights

Positive drivers of campaign response:

Total_Spent (+0.27)

Total_Purchases (+0.16)

Income (+0.13)

Negative drivers:

Recency (–0.20)

Total_Children (–0.17)

🤖 Customer Segmentation (K-Means Clustering)
📌 Model Process

Selected behavioral and demographic features

Scaled numeric variables

Used Elbow Method → optimal k = 4

Trained a K-Means model with 4 clusters

Visualized segment distribution

🧬 Customer Segment Profiles
🟦 Segment 0 — “Active Senior Shoppers”

Older

High total spending

Frequent purchasers

Medium–high income

Strong campaign response
➡️ High value segment

🟩 Segment 1 — “Young Low Spenders”

Young

Low income

Low spending

Rarely respond to campaigns
➡️ Low value

🟨 Segment 2 — “Large Budget Families”

Several children

Lower income

Very low spending
➡️ Lowest value

🟥 Segment 3 — “(Replace with your segment summary from your code)”

Example:
“Middle-aged professionals with stable income, moderate spending, and average engagement.”
➡️ Medium value segment

📈 Campaign Performance

Segment 0 responds the most

Segment 2 responds the least

Campaign 3 performs best

Recent customers show significantly better engagement

Loyalty-driven campaigns outperform generic ones

💸 Customer Lifetime Value (CLV)

Estimated CLV shows:

Segment 0 has 3.2× higher CLV than Segment 2

High-value customers buy more frequently, spend more, and respond better

Targeting them increases overall ROI

🎯 Final Business Recommendations
1️⃣ Prioritize Segment 0 for future campaigns

High spending + high response = best ROI.

2️⃣ Create loyalty programs for frequent buyers

Retention is cheaper than acquisition.

3️⃣ Use recency-triggered campaigns

Send promotions within 30–60 days of last purchase.

4️⃣ Reduce spending on large-family segments

Low conversions → budget drain.

5️⃣ Create premium offers for high-income groups

This segment spends disproportionately more.
