
DASHBOARD AND STORYTELLING – README

Project Title:

Life Style of a Community – A Data Visualization Story Using Power BI

Objective:

To analyze and visualize lifestyle patterns across different community types using demographic, behavioral, and campaign response data. The goal was to transform a raw marketing dataset into a human-centered dashboard that reflects income, education, engagement, and emotional context.

Dataset Source:

Original dataset provided by Elevate Labs as part of internship onboarding. It contained 29 fields related to customer demographics, campaign responses, and product purchases.

Tools Used:

- Microsoft Excel (for data cleaning, column engineering, binning, and documentation)
- Power BI Desktop (for dashboard visualization and storytelling)
- Manual logic only. No Python, DAX, or automation used

Development Process:

1. Initial Exploration
   - Reviewed all 29 original fields
   - Identified key drivers: Marital_Status, Income, Education, Campaign Response

2. Data Cleaning and Engineering (Excel)
   - Created new columns:
     - TotalAcceptedCmp
     - MntMarketProductsUse
     - NumPurchasesAndVisitsInMonth
     - IncomeGroup (binned)
     - CommunityType (derived from Marital_Status + Kidhome)
   - Validated formula logic manually
   - Documented all original and modified fields for reproducibility

3. Storyboard Planning
   - Erased and rebuilt storyboard multiple times
   - Reframed Marital_Status as a central emotional driver
   - Segmented visuals by behavior, not just economics
   - Chose realistic, community-focused imagery to support narrative

4. Visualization (Power BI)
   - Designed visuals:
     - Donut chart: IncomeGroup by CommunityType
     - Clustered column chart: Campaign Response by CommunityType
     - Treemap: Income by CommunityType and IncomeGroup
     - Bar chart: Education vs Response
   - Applied realistic background image of a residential community
   - Added human-centered visuals (income counting, campaign participation, education)

5. Storytelling Logic
   - Focused on emotional resonance and behavioral insight
   - Used intuitive naming for columns and charts
   - Avoided technical jargon to make dashboard recruiter-friendly
   - Created insight cards and narrative captions to guide viewer interpretation

6. Documentation
   - Created README to capture full development journey
   - Included dataset summary, column logic, and storytelling rationale
   - Prepared for future reuse and portfolio presentation

Dataset Summary:

Field Name                        | Description
----------------------------------|-----------------------------------------------
IncomeGroup                       | Binned income levels (Low, Middle, High)
CommunityType                     | Derived from Marital_Status and Kidhome
TotalAcceptedCmp                  | Sum of accepted campaigns
Response                          | Campaign response flag
Education                         | Qualification level (Graduation, PG, Master, Doctorate)
NumPurchasesAndVisitsInMonth      | Monthly engagement score
MntMarketProductsUse              | Monthly spend on market products

Status:
-------
Dashboard is complete and ready for presentation.
All visuals, logic, storytelling elements, and documentation have been finalized.

Author’s Note:
--------------
This dashboard was built manually—without Python, DAX, or automation. Every chart, column, and image reflects intentional storytelling and community empathy. It’s not just a data project—it’s a portrait of people.