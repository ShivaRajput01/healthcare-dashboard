# Healthcare Dashboard in Power BI

## Project Overview

This Power BI Dashboard is designed to provide comprehensive insights into various healthcare metrics. The dashboard includes key information on patient demographics, billing data, bed occupancy, feedback for doctors, insurance vs billing statistics, and diagnosis trends. The goal of this project is to enable healthcare administrators and stakeholders to analyze and monitor essential healthcare data for improved decision-making and resource management.

## Features and Visualizations

1. **Patient Information (by Patient ID)**  
   Displays detailed patient data including:
   - Patient ID
   - Name, Age, Gender
   - Admission Date, Discharge Date
   - Patient Status
   - Medical History and Diagnosis

2. **Billing Information**  
   Provides a breakdown of billing details, showcasing:
   - Total billing amounts
   - Payment statuses (Paid, Pending, Overdue)
   - Types of medical procedures or services provided and their corresponding costs

3. **Bed Occupancy Breakdown**  
   This section tracks bed usage across the healthcare facility:
   - Total beds available vs. currently occupied beds
   - Occupancy rate by department or unit
   - Historical trends in bed occupancy

4. **Doctor Feedback**  
   Provides aggregated feedback from patients regarding doctor performance:
   - Average ratings on doctor interactions
   - Feedback trends over time
   - Comparison of ratings across different doctors or departments

5. **Billing vs. Insurance**  
   Displays a comparison between billed amounts and the insurance claims processed:
   - Total billed amount
   - Total insurance claims approved/processed
   - Out-of-pocket costs for patients
   - Claim approval vs. denial trends

6. **Diagnosis Statistics**  
   Provides a detailed breakdown of the diagnoses:
   - Frequency of each diagnosis
   - Trends in common diagnoses across various departments
   - Top diagnoses by patient demographics (e.g., age, gender)

## Data Sources

- **Patient Data**: Sourced from the hospital's patient management system, including demographic and admission details.
- **Billing Data**: Collected from the hospital's financial system, covering all billing transactions.
- **Bed Occupancy**: Data pulled from the hospital's room management system.
- **Doctor Feedback**: Compiled from patient surveys and feedback forms.
- **Insurance Data**: Extracted from the hospital's insurance claim system.
- **Diagnosis Data**: Sourced from the hospital's diagnostic records and healthcare databases.

## Key Insights

- **Patient Insights**: Helps to identify the most common patient demographics and their healthcare needs.
- **Operational Efficiency**: Provides visibility into bed occupancy rates, assisting in resource management and planning.
- **Financial Analysis**: Enables stakeholders to evaluate the performance of billing processes and insurance claims handling.
- **Doctor Performance**: Helps improve the quality of care by tracking patient feedback and identifying opportunities for improvement.
- **Diagnostic Trends**: Facilitates better diagnosis resource allocation based on common health conditions.

## Installation

To view and interact with this Power BI Dashboard:

1. Download the Power BI file (PBIX) from the repository.
2. Open the file using [Microsoft Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).
3. If necessary, connect to the data sources by configuring credentials for the relevant databases.
4. Refresh the data to load the latest records.

## Technologies Used

- **Power BI**: For creating the interactive dashboard and visualizations.
- **Data Models**: Designed with DAX (Data Analysis Expressions) and Power Query.
- **Data Sources**: SQL databases, CSV files, Excel sheets (depending on the data extraction process).

## Future Enhancements

- Integration with real-time data sources for continuous monitoring of bed occupancy and billing.
- Additional drill-through options for more granular patient, doctor, and billing insights.
- Incorporation of predictive analytics for patient outcomes and cost forecasting.

