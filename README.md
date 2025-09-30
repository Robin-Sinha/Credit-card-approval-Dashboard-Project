# Credit-card-approval-Dashboard-Project
🔹 Project Overview
This is a Power Bi dashboard project

This project analyzes credit card applications to understand key factors influencing approval rates.
The dataset is based on anonymized credit data, where categorical variables (like employment, gender, etc.) are coded.
The goal is to demonstrate data cleaning, transformation, and visualization skills in Power BI.

🔹 Dataset

Source: [UCi Credit Approval Dataset] 

Rows: ~690 applications

Columns: 15 attributes (Age, Gender, Income, Prior Default, Employment, etc.)

Target: Approval Status (Approved / Rejected)

🔹 Data Cleaning & Transformation

Handled missing values (Age blanks → "Unknown").

Replaced coded values with meaningful labels (e.g., a/b → Male/Female).

Created calculated columns (Age Group, Income Group).

Built a DAX measure for Approval Rate.

🔹 Dashboard Features

KPIs: Approval Rate, Rejection Rate, Total Applications.

Charts:

Approval Rate by Age Group

Approval Rate by Income Group

Approval Rate by Gender

Approval Rate by Prior Default

Approval rate by debt group

Filters (Slicers): Age group , Prior default status 

🔹 Key Insights

Applicants with prior defaults had a much lower approval rate.

Approval rate increases with higher income and longer employment (stability factor).

There are missing values in Age/Gender — real-world data challenge that was addressed in cleaning.

🔹 Tools Used

Power BI Desktop

DAX for calculated measures

Power Query for data cleaning

“The dataset contained anonymized columns such as Employment Years coded as letters. Instead of making incorrect assumptions, I either kept them as categorical proxies or dropped them, focusing on features like income, prior default, and debt that gave clearer business insights.”

Since the dataset was anonymized, these mappings are assumptions for analysis, not definitive labels.”
