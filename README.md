# POWER-BI-TASK_6

# Healthcare Data Analysis Dashboard – Power BI

## 1. Project Overview

This project uses Microsoft Power BI to explore healthcare and hospital admission data. The report summarizes admissions by hospital, admission type, age group, and year. It also presents key figures and allows users to filter the report by admission type and insurance provider.

## 2. Tools Used

- Microsoft Power BI Desktop
- Power Query Editor for data preparation and transformation
- Data/Model view for organizing tables and relationships
- Report view for building visuals and the dashboard

## 3. Data Used

The main report visuals use the `healthcare_dataset` table. The model also includes date and dimension tables such as `DimDate`, `DimPatient`, `Dim Doctor`, `Dim Hospital`, and `FactAdmission` where available in the file/model.

Important fields used in the report include Hospital, Admission Type, Age Group, Date of Admission, Gender, Medical Condition, Insurance Provider, and measures such as Total Admissions, Total Patients, and Average AGE.

## 4. Operations Performed in Power BI

### 4.1 Imported healthcare data
Loaded the healthcare dataset into Power BI to use as the source for analysis.

### 4.2 Prepared and organized data
Used Power Query/data-model features to prepare the data and organize relevant fields for reporting. Review the Applied Steps in Power Query for the exact transformation sequence saved in the file.

### 4.3 Organized tables and date information
Used date-related fields for year-based analysis and included date/dimension tables in the model where configured. This supports grouping and analysis across time and healthcare categories.

### 4.4 Created summary measures
Used report measures including **Total Admissions**, **Total Patients**, and **Average AGE** to summarize the dataset in the visuals.

### 4.5 Created KPI cards
Added card visuals to show:
- Total Patients
- Average AGE

These cards provide quick summary figures for the report.

### 4.6 Created a clustered column chart by hospital
Created a clustered column chart with **Hospital** on the category axis and **Total Admissions** as the value to compare admissions across hospitals. The chart is sorted by Total Admissions in descending order.

### 4.7 Created a pie chart by admission type
Created a pie chart showing **Total Admissions** split by **Admission Type** to compare the contribution of each admission category.

### 4.8 Created a pie chart by age group
Created a pie chart showing **Total Admissions** by **Age Group** to compare admissions across age categories.

### 4.9 Created a line chart for yearly admissions
Created a line chart using the **Year** from Date of Admission and **Total Admissions** to show the yearly trend in admissions.

### 4.10 Created a gender comparison chart
Created a clustered column chart with **Year** as the category, **Gender** as the series, and **Count of Gender** as the value. This compares gender counts across years.

### 4.11 Created a matrix/table visual
Created a matrix visual with **Age Group** as rows, **Medical Condition** as columns, and **Total Admissions** as values. This supports comparison of admissions by age group and medical condition.

### 4.12 Added slicers for interactive filtering
Added slicers for:
- Admission Type
- Insurance Provider

Users can select values in these slicers to filter the report visuals.

### 4.13 Formatted the report page
Configured the report page as **Page 1** and set the page display option to **Fit to Page** so the dashboard fits within the report area.

### 4.14 Applied report theme and settings
The report includes the **Fluent 2** base theme and a dark custom theme resource. Report settings support summarized-data export and visual drill/filter interactions.

## 5. Visuals Included

| Visual | Purpose |
|---|---|
| Card – Total Patients | Shows the total patient count measure |
| Card – Average AGE | Shows the average age measure |
| Clustered column chart – Hospital | Compares total admissions across hospitals |
| Pie chart – Admission Type | Shows admissions by admission type |
| Pie chart – Age Group | Shows admissions by age group |
| Line chart – Year | Shows the trend in total admissions over years |
| Clustered column chart – Gender by Year | Compares gender counts across years |
| Matrix – Age Group and Medical Condition | Compares admissions by age group and medical condition |
| Slicer – Admission Type | Filters the report by admission type |
| Slicer – Insurance Provider | Filters the report by insurance provider |

## 6. Power BI Concepts Practiced

- Data import and preparation
- Data modeling and date-based grouping
- Measures and aggregations
- KPI cards
- Clustered column charts
- Pie charts
- Line charts
- Matrix visuals
- Slicers and interactive filtering
- Sorting visual data
- Report page formatting and themes

## 7. Screenshot

<img width="1328" height="742" alt="Screenshot 2026-10-16 182456" src="https://github.com/user-attachments/assets/cf066d1f-4ef8-45f5-9b44-538793dc7190" />


## 8. Conclusion

This Power BI task demonstrates how healthcare data can be summarized in an interactive dashboard. KPI cards provide quick totals, charts compare admissions across hospitals and categories, the line chart shows yearly trends, and slicers allow users to explore the data by admission type and insurance provider.

## Note

This README documents the report visuals and settings visible in the supplied PBIX file. For a complete record of data-cleaning steps, check **Transform data → Applied Steps** in Power BI Desktop, because the exact sequence of every Power Query transformation is not fully represented by the report visuals alone.
