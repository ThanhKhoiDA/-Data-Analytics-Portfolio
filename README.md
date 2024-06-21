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
- ** ⚧️ Gender Distribution**
    - The proportion of men using the service is higher than that of women in all age groups, with the male group from 23-27 accounting for the highest proportion (15.15%).
### 📢 Transaction Behavior
- ** 📺 Revenue by Merchant:** Viettel leads in average monthly revenue (596,033 VND), followed by Mobifone and Vinaphone. Gmobile has the lowest revenue.
- ** 🏡 Location-Based Transaction Amount:** Users in other regions (besides HCMC and Hanoi) tend to spend more, especially the age group from 23-27. Meanwhile, HCMC and Hanoi have lower but still significant spending levels.
































