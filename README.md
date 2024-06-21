# 📊 Optimize MoMo Operations and Enhance User Experience through Mobile top-up service Analytics

## 🎯 Introduce the Topic and Its Objectives
- 📱 Mobile Topup (Topup service) is one of MoMo's most important services with a large proportion of users and revenue. Topup service on the MoMo app is displayed under two icons: 'Nạp tiền điện thoại' and 'Mua mã thẻ di động'.

- 🔍 This analysis will focus on exploring and analyzing the dataset from the "MoMo Talent 2024" competition. 

- 🎯 The goal of this analysis is to uncover trends, patterns, and correlations between the variables in the dataset, thereby providing valuable recommendations for the business. Understanding this data not only helps optimize MoMo's business operations but also enhances user experience through more personalized services.

## 📂 Dataset
The dataset used in this project is obtained from ["MoMo Talent 2024" competition](https://drive.google.com/drive/folders/1N7tz3jwrw9DyWpbB4JPajGAVUK44do0T). The dataset includes information on transactions, commissions, and user information, stored in three main tables:

- **📅 "Data Transactions":** Historical daily transactions data during Jan-Dec 2020.
- **📅 "Data Commission":** The percentage of commission paid by the Telco's merchants to MoMo.
- **📅 "Data User_Info":** The users' demographic information.

## 🛠️ Tools 
- **🔧 Tools Used:** Power BI, Power Query Editor, DAX.

## 🛠️ Implementation

### 🗂️ Data Collection
- Downloaded the dataset from MoMo and imported it into the project environment using Power Query Editor for initial data exploration.

### 🧹 Data Cleaning
- Transformed data using Power Query Editor to ensure consistency and accuracy.
- Removed duplicate entries to prevent skewing the analysis.
- Re-synchronize date format for consistency.
- Replace null values ​​in the "Purchase_status" column with the value "Tự mua".
- Resynchronize values ​​in the "Location" & "Gender" columns.
- Edit the values ​​in the "Age" column for brevity.

### 📊 Data Analysis
- Renamed columns for clarity and created calculated columns as needed to derive additional insights.
- Established relationships between different tables (e.g., customer demographics, service usage) to facilitate comprehensive analysis.
- Applied statistical techniques, such as correlation analysis, to identify relationships between variables.

### 📈 Result Visualization
- Create a layout of key metrics including "Total Amount", "Revenune", "Total Orders" in large sizes on the left side of the dashboard.
- Developed various charts, graphs, and other visual representations (e.g., bar charts, pie charts, scatter plots) to illustrate findings.
- Used slicers and filters in Power BI to allow interactive exploration of the data.
## 💡 Observations and Insights
### 👨‍👩‍👧‍👦 User Demographics
- **🎂 Age Distribution**
    - Users in the 23-27 age group account for the highest proportion (25.48%), followed by the 28-32 group (20.84%).
    - Age groups from 33-37 and 18-22 also account for a significant but lower portion.
    - This shows that the majority of MoMo users are of young working age and students.
- **⚧️ Gender Distribution**
    - The proportion of men using the service is higher than that of women in all age groups, with the male group from 23-27 accounting for the highest proportion (15.15%).
### 📢 Transaction Behavior
- **📺 Revenue by Merchant:** Viettel leads in average monthly revenue (596,033 VND), followed by Mobifone and Vinaphone. Gmobile has the lowest revenue.
- **🏡 Location-Based Transaction Amount:** Users in other regions (besides HCMC and Hanoi) tend to spend more, especially the age group from 23-27. Meanwhile, HCMC and Hanoi have lower but still significant spending levels.
- **🔠User Type:** The proportion of "NEW" accounts for 99.27% ​​of the total. Customer only used it once and has not used it again.
   - ⚠️ **THE SERVICE MAY HAVE ERRORS, BAD POINTS, OR POOR CUSTOMER CARE DURING USE** 

## 🔔 Advice for the Marketing department in designing promotion campaigns to increase Topup's monthly performance
### 📋 SURVEY
- Create a survey with a discount code to top up mobile phones for old MoMo customers about the Top-up service to find out why customers do not use the service again.
### 🎯 Targeted Promotions for Young Adults
- Focus on the young user group (23-27 years old) with attractive promotional campaigns such as higher cashback, gifts when depositing, or special discounts on cooperative services.
### ⚧️ Gender-Specific Campaigns
- Design promotional programs suitable for men, because the rate of men using the service is higher. For example, promotions related to sports, technology or consumer products that are popular with men.
### 🏙️ Location-Based Incentives
- Provide special incentives for users in other regions (outside HCM and Hanoi) to stimulate them to deposit more.
### 👫 Referral and Loyalty Programs
- Create refer-a-friend and loyalty programs to encourage existing users to refer friends and deposit regularly.

## 🏇 Compete for Cashback with Other E-wallets
### 🚨 Momo is facing stiff competition from a host of other e-wallets that have deep mobile card cashback schemes for users. In response, MoMo is considering deducting a part of revenue to increase cashback for users in all Telco merchants.
- Suppose that users currently earn a flat 1% cash-back on their spending amount. The proposed change is as follows:

| Merchant | % cashback (current) | % cashback (proposal) |
| :--- | :--- | :--- | 
| Viettel | 1 | 2 |
| Mobifone | 1 | 2.5 |
| Vinaphone | 1 | 3 |
| Vietnamobile | 1 | 3 |
| Gmobile | 1 | 3 |

- How does this affect the service (Comment from many perspectives)? Do you agree with this option?
  
### ⚖️ Analysis from Multiple Perspectives

### 1️⃣ User Perspective:
  - **Positive Impact:**
      - **Increased Cashback Incentive:** Users gain more value per transaction, promoting more frequent use of MoMo's services, especially with high cashback providers like Vinaphone and Vietnamobile.
      - **Enhanced Customer Satisfaction:** Higher cashback improves user satisfaction, boosting retention and user experience.
 - **Negative Impact:**
      - **Short-Term Expectations:** Users may expect continued or increased cashback, potentially pressuring MoMo to maintain these offers.
        
### 2️⃣ Financial Perspective:
  - **Short-Term Revenue Loss:**
      - **Direct Cost:** Higher cashback rates reduce short-term profits as more revenue is returned to users.
      - **Budget Reallocation:** MoMo must carefully manage its budget to prevent negative impacts on other business activities.
  - **Long-Term Financial Gains:**
      - **Increased Transaction Volume:** Higher cashback rates can boost transaction numbers and total revenue from both existing and new users.
      - **Customer Retention and Acquisition:** Better retention and new customer acquisition can offset short-term revenue losses, leading to long-term profits.
        
### 3️⃣ Competitive Perspective:
  - **Strengthened Competitive Position:**
      - **Market Differentiation:** Offering superior value through higher cashback can differentiate MoMo from competitors.
      - **Increased Market Share:** Higher cashback rates can attract users from other e-wallets, expanding MoMo's market share and strengthening its market position.
  - **Market Reactions:**
      - **Competitive Response:** Competitors may increase their promotions, leading to a potential promotional war. MoMo needs to stay flexible in its business strategy to respond effectively.

#### 👌 Do you agree with this option?
- I agree only if this campaign is applied for a short period of time, long enough for momo to find out the reason why most current customers do not use the service again.
- Once you have found the reason why customers do not use the service again. I recommend that momo stop this campaign and return to the original refund level.
#### ⏲️ After a while, you can stop this refund offer and instead run other campaigns to both retain customers and optimize revenue such as:
- Accumulate points to redeem phone recharge card codes
- Introduction to receive phone recharge card code
- Refund for premium customers,...

#### ☑️ Because the race for refund rates between e-wallet providers will lead to an endless promotion war and businesses will suffer heavy losses. This is only suitable for the early stages of business development when getting acquainted with the market and approaching customers.

#### 📋 A typical example is that Techcombank has a 1% cashback offer on all card transactions applicable to all card types and all customers. Up to now, Techcombank has eliminated this incentive and replaced it with other new incentives to both retain customers and optimize its profits.

































