# Data-205 Capstone Project
## City of Rockville Population Projections and Dashboard
  City of Rockville Community Planning and Development Services internship involved creating a dashboard that displayed visualizations for demographic, economic, housing and population forecasts 
 from U.S. Census Data.  Secondly, estimate future city’s population by age and sex in five-year increments as a tool to review future housing needs pertaining to volume and affordability. 
 ### Dashoard
 The 2020 Decennial Census and the American Community Survey 1-Year and 5-Year Estimates Data Profiles were used to make visualizations in Power BI. The excel files from the Census Bureau did not require any cleaning.  The pre-processing methods used was filtering and subgrouping techniques for the visualizations. Additionally, data that required subgrouping, the margin of errors were pooled with the use of a online calculator from https://www.datacenterresearch.org/data-resources/neighborhood-data/combining-data-points/  and subject matter expert review. For additional information, the user may hover over a visualization and a tool-tip box will appear with additional information.  There are links embedded in the title box that takes the user to the Rockville Community Planning page and another link in the sources text box that takes the user to the U.S. Census Bureau home page. The full PDF dashboard and EXCEL files are available in this repository. An example page of Housing Characteristics is listed below:
 
![image](https://github.com/user-attachments/assets/f922c76b-0077-41d2-af60-993dc472bc36)

### Population Estimates for Age and Sex Groups
The City is concerned about future housing needs.  The number, type (single, single attached, multi-family units, senior) and affordability of housing is of equal concern. Future population estimates that include age and sex cohorts at a city level is not readily available.  This project entails projecting future population estimates to the year 2040 from the U.S. Decennial 2010 and 2020 Census’ age and sex categories in five-year increments; and comparing future population estimates to future approved housing projections.

The Hamilton-Perry method is considered an acceptable method for use for subcounty areas in estimating future population projections. The data requirements are the use of two most recent U.S. Census periods   It utilizes cohort change ratios (CCR) which addresses deaths and net migration; and the Child Women Ratio (CWR) which represents surviving births. Using the Hamilton-Perry method, both ratios(CCR, CWR) and population estimations in 10-year increments were calculated using basic EXCEL functions. In order to project 5-year projections, a Linear Interpolation was applied by using the the EXCEL FORECAST.Linear function to the 10-years estimates. The final population estimates are in the repository.

Evaluating the accuracy of the projections for years 2030 to 2040 is problematic, as the data is not yet available. According to the literature (Baker, et al, 2020), the Hamilton-Perry average error rate for county projections ranges from 6% to 16%. Based on the City of Rockville’s population of 67,000 and it is approximately around the 75th percentile for all U.S. counties, it is surmised that this error rate would apply.

### Comparison of Future Population Estimates to Future Projected Housing Estimates
A comparison was made between the future population estimates to the number of residential projects that have been approved (not built) for the 2020-2040 time period. To convert the residental projects to population numbers, a 2020 population multiplier was applied to each type of approved residental housing type (Single Family-Detached, Single-Family Attached, Multi-Family, Senior). Overall, from 2020 to 2040, the population projection will grow by 13,729 people; projected future housing will approximately serve 13,573 people. The are additional housing projects in the pipeline for this time period that were not included these calculations. The senior population (80+) is projected to grow by 1730 people, projected housing estimate will serve approxmately 1,011 people. Currently there is no additional senior housing in the pipeline.






