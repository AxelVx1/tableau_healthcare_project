# tableau_healthcare_project

## Overview
This project analyzes healthcare billing data and patient length of stay across various hospitals. The goal is to provide insights into healthcare costs, patient outcomes, and hospital performance. The interactive dashboard was built using Tableau, and the data has been analyzed to answer key business questions related to cost optimization and operational efficiency.

## Dataset
- **Source**: The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/), which provided a synthetic healthcare dataset. It contains patient information, admission details, billing amounts, and other healthcare-related attributes.
- **Data Size and Attributes**: The dataset includes information such as:
  - `Age`, `Gender`, `Blood Type`
  - `Medical Condition`
  - `Hospital`, `Doctor`, `Insurance Provider`
  - `Admission Type`, `Length of Stay`, `Billing Amount`
  - `Date of Admission`, `Discharge Date`
- **Purpose of Dataset**: The dataset was used to analyze healthcare billing, hospital performance, and patient outcomes.

## Data Cleaning
After downloading the dataset from Kaggle, the data cleaning process was performed using Microsoft Excel to ensure that the data was accurate and ready for analysis. The key data cleaning steps included:

1. **Fixing Inconsistent Values**:
   - **Hospital Names**: Corrected inconsistent hospital names (e.g., removed entries that began with "and" or ended with a comma).
   - **Doctor Titles**: Removed prefixes like "Mr." and suffixes like "PhD" or "MD" to standardize the names of doctors.

3. **Calculating New Fields**:
   - Added a calculated column for **Length of Stay**, based on the difference between admission and discharge dates.

4. **Handling Negative Billing Amounts**:
   - Identified and reviewed negative billing amounts to determine if they were refunds, adjustments, or errors. Decided whether to include or exclude these records in the analysis.

5. **Dropping Duplicate Values**:
   - Identified and removed any duplicate records to ensure that each patient visit was unique. This step helped to prevent inflated counts or incorrect aggregate calculations.

After cleaning the data in Excel, it was saved as a `.csv` file for importing into Tableau for further analysis and visualization.

## Interactive Dashboard
The interactive Tableau dashboard is available here: https://public.tableau.com/app/profile/axel.rodriguez5371/viz/HealthInsuranceDashboard_17292722821110/HealthInusranceDashboard?publish=yes

