# Price Index of Operating Costs (PIOC)
**Developed by**: Itzamna Huerta, for the Association for Neighborhood and Housing Development (ANHD)  
**Created**: Feb 2025  
**Last Updated**: N/A  

#### Overview
The Price Index of Operating Costs (PIOC) is an annual report published by the New York City Rent Guidelines Board (RGB), tracking changes in the costs of maintaining rent-stabilized housing. This project automates the extraction and analysis of PIOC data to support advocacy efforts, policy analysis, and preservation campaigns.

By systematically collecting and analyzing cost trends, this project provides insight into the financial pressures faced by property owners of rent-stabilized units, informing decisions on affordability policies and tenant protections.

#### Objectives
<u>Extract Key Variables</u>: Identify and capture percentage changes for major cost categories:
- Rent Stabilized Apartments increased
- Real estate taxes
- Insurance Costs
- Adminstrative Costs
- Maintenance 
- Utilities
- Labor Costs
- Fuel 
- Natural Gas & Fuel Oil Heat
- Costs in Pre-1974 Buildings
- Buildings that contain ret stabilized apartments

<u>Standardize Data</u>: Clean and structure extracted values to ensure consistency across multiple years.

<u>Analyze Cost Trends</u>: Compile data into a structured format for visualization and policy analysis.


#### Methodology
1. Text Extraction & Preprocessing: Extract relevant text from PIOC PDF reports, clean and standardize formatting.
2. Pattern Matching: Use regex-based searches to locate and extract percentage changes associated with key cost categories.
3. Multi-Year Data Compilation: Iterate through multiple reports, associate extracted values with corresponding years, and consolidate into a structured dataset.
4. Data Transformation & Visualization: Convert data into a numerical format, reshape for analysis, and prepare for visualization.
