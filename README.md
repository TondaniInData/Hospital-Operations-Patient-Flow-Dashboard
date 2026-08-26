Hospital Operations & Patient Flow Dashboard

Power BI | Power Query | DAX | Healthcare Analytics

An interactive Power BI dashboard analysing hospital patient activity, operational workload, clinical case characteristics and revenue patterns. The project explores patient volume, length of stay, case severity, specialty activity and payer contribution to identify patterns that may support hospital management and further investigation.

Project Overview

Hospital management needs visibility into patient demand, operational workload, clinical complexity and financial activity in order to understand how the hospital is performing.

This project uses a hospital operations dataset to develop an interactive Power BI report that brings these areas together.

The analysis follows the journey:

Patient Activity → Operations → Clinical Profile → Revenue → Insights

The objective was not simply to create visualizations, but to use the available data to answer practical stakeholder questions and identify areas that may require further investigation.

Business Problem

Hospital stakeholders need to understand:

How much patient activity the hospital is handling
Where patient activity is concentrated
Which specialties experience higher workloads
How length of stay varies across the hospital
What the clinical severity profile looks like
Where high-severity cases are concentrated
Which specialties contribute most to revenue
Which payer groups contribute most to revenue
How revenue changes over time
Whether high patient volume corresponds to higher financial contribution

The dashboard was designed to provide a consolidated view of these areas.

Stakeholder Questions

The analysis was structured around the following questions:

Patient Activity
What is the overall patient/case volume?
How does patient activity change over time?
Which specialties handle the greatest volume?
Operations
Where is operational workload concentrated?
Which specialties have longer average lengths of stay?
Are there areas where high volume and longer stays occur together?
Clinical Profile
What is the distribution of case severity?
How does severity vary across age groups and gender?
Which specialties have a higher concentration of severe cases?
How does length of stay vary by severity?
Revenue
How much revenue is generated?
What is the average revenue per case?
Which specialties contribute the most revenue?
Which payer groups contribute the most revenue?
How does revenue change over time?
Are there differences between patient volume and revenue contribution?
📊 Dashboard Structure

The Power BI report contains four analytical pages and a dedicated insights page.

01 - Hospital Overview

<img width="1102" height="612" alt="image" src="https://github.com/user-attachments/assets/b14e649c-032e-4d38-a583-bae719f702ae" />


The page is designed to give stakeholders an immediate understanding of the overall hospital picture .
02 - Patient Volume & Operations

Focuses on patient activity and operational workload.

Key areas include:

Patient volume
Patient activity over time
Specialty workload
Length of stay
Patient volume and operational patterns

Main question:

Where is hospital activity and operational workload concentrated?

03 - Clinical & Case Profile

Focuses on the characteristics and complexity of the cases being treated.

Key areas include:

Case severity distribution
Patient age profile
Severity by age group
Severity by gender
Severity by specialty
Average length of stay by severity

Main question:

What does the hospital's clinical case profile look like?

04 - Revenue & Payer Insights

Focuses on the financial contribution associated with hospital activity.

Key areas include:

Total revenue
Average revenue per case
Revenue by payer
Revenue by specialty
Revenue trends
Payer composition

Main question:

What is driving the hospital's revenue?

05 - Key Insights

The final page brings the analysis together by highlighting:

Patient and demand patterns
Operational observations
Clinical patterns
Revenue observations
Areas requiring further investigation
Data limitations
Data Preparation

Power Query was used to prepare the dataset before building the report.

The preparation process included:

Reviewing and correcting data types
Standardizing categorical fields
Investigating missing values
Validating date-related fields
Creating analytical fields such as age groups
Renaming fields for business readability
Removing or excluding unsuitable fields
Checking the overall quality and consistency of the data
DAX Measures

Several DAX measures were created to support the analysis.

Examples include:

Total Cases
Total Revenue
Average Revenue per Case
High Severity %

These measures were used throughout the report to create interactive KPIs and visualizations.

Key Visualizations

The report includes visualizations such as:

KPI cards
Column charts
Bar charts
Line charts
100% stacked charts
Scatter plots
Matrix/heatmap analysis
Interactive slicers

The visuals were selected based on the stakeholder questions they were intended to answer rather than simply displaying available fields.

Interactivity

The dashboard allows users to explore the data using filters such as:

Month
Specialty
Payer
Insurance Plan
Age Group
Other relevant report dimensions

This allows stakeholders to move from a high-level overview into more specific areas of the hospital.

Key Insights

The final insights are based on the patterns identified within the completed Power BI report.

Examples of areas investigated include:

Concentration of patient activity across specialties
Differences in length of stay
Distribution of case severity
Specialties associated with more severe cases
Revenue contribution across specialties
Revenue contribution across payer groups
Differences between patient volume and revenue contribution

Note: Final numerical findings will be documented here after the analysis has been fully validated.

Limitations

The analysis is based entirely on the information available in the supplied dataset.

Although the dataset supports analysis of patient activity, operations, clinical characteristics and revenue, it does not provide all information required to assess complete hospital profitability.

For example, additional information such as:

Operating costs
Staffing levels
Reimbursement rates
Claim status
Departmental expenses
Profit margins

would be required for a more comprehensive financial analysis.

Therefore, the dashboard identifies patterns and areas for further investigation rather than establishing causal relationships or making definitive operational decisions.
Tools & Technologies
Tool	Purpose
Power BI	Dashboard development and data visualisation
Power Query	Data cleaning and transformation
DAX	Measures and analytical calculations
