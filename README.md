# HR Analytics & Attrition Dashboard: Strategic Workforce Insights

## 📊 Project Overview
This project is a comprehensive HR Data Analysis designed to identify key drivers of employee attrition and provide actionable insights for strategic workforce management. Using a multi-dimensional dataset, I developed an interactive Power BI dashboard that translates complex HR metrics into executive-ready visualizations.

## 🚀 Key Insights & Business Impact
*   **The Promotion Lag Effect**: Identified a critical attrition spike (37.87%) among employees who haven't received a promotion within their first year, suggesting a need for earlier career pathing interventions.
*   **Overtime Burnout**: Discovered that employees working overtime are 3x more likely to leave (30.53% attrition rate), highlighting a direct correlation between workload and retention.
*   **High-Performer Retention Gap**: Uncovered a significant salary disparity where high-performing leavers were paid ~35% less than stayers, indicating a need for targeted pay-equity reviews.
*   **The "Onboarding Trap"**: Analyzed new joiner attrition to identify specific departments and education fields where early-stage turnover is highest.

## 🛠️ Technical Stack
*   **Tool**: Power BI Desktop
*   **Data Modeling**: Star Schema (1 Fact Table, 4 Dimension Tables)
*   **DAX (Data Analysis Expressions)**: Developed 15+ custom measures for KPIs, Year-over-Year growth, and segmented attrition rates.
*   **Data Visualization**: Advanced use of clustered columns, donut charts, line trends, and conditional formatting.

## 📂 Repository Structure
*   `Data/`: Contains the 5 CSV files used for the analysis (Employee, Performance, Satisfaction, etc.).
*   `Dashboard/`: The `.pbix` file (Power BI Desktop file).
*   `Documentation/`: Detailed analysis report and DAX formula guide.
*   `Assets/`: Custom-designed cover page and dashboard banners.

## 📈 Dashboard Preview
<img width="6150" height="3525" alt="Graduation Project - 0002" src="https://github.com/user-attachments/assets/45332f4f-27b3-463c-a68f-1c1874b8c511" />

<img width="6150" height="3525" alt="Graduation Project - 0003" src="https://github.com/user-attachments/assets/1f20de90-4caa-4334-9940-64f2f41061d4" />

<img width="6150" height="3525" alt="Graduation Project - 0006" src="https://github.com/user-attachments/assets/b6223d92-c4ad-46c1-ba71-d09de061ae6e" />

## ⚙️ How to Use
1.  Clone this repository.
2.  Open the `.pbix` file in **Power BI Desktop**.
3.  Ensure the data source paths point to the CSV files in the `Data/` folder.
4.  Explore the interactive visuals using the slicers for Department, Job Role, and Gender.
