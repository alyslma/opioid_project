# Fatal Opioid Overdoses and Prescriptions

![Title Slide](visualizations/ppt_title.jpg)

[PDF file of PPT slides](opioid_project_slides.pdf)

## Purpose
- To determine if there are demographic groups or locations where fatal opioid overdoses are more prevalent, and if so, if there is a relationship between prescribing practices and opioid related mortalities in these demographics/locations

## Data Sources and Tools
- Multiple Cause of Death (1999-2018) from [CDC Wonder](https://wonder.cdc.gov/mcd-icd10.html)
- Opioid Overdose Deaths by Age Group from [Kaiser Family Foundation (KFF)](https://www.kff.org/other/state-indicator/opioid-overdose-deaths-by-age-group/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D)
- Medicare Part D Opioid Prescriber Summary File 2017 from [CMS](https://data.cms.gov/Medicare-Part-D/Medicare-Part-D-Opioid-Prescriber-Summary-File-201/sakz-a2rp)
- Python, Jupyter Notebook, Pandas, Matplotlib, and Google APIs

## Visualizations
- Stacked bar graph and line graph of opioid-related deaths per 100k population by age group per year (2009-2018)
- Percent change in opioid deaths by age group (2009-2018)
- Heat map showing the % of opioid-related deaths for 55+ in the United States (2009-2018)
- Top five states with highest number of 55+ opioid deaths per 100k
- Choropleth map showing the number of top opioid prescribers for Part D population by state (2017)
- Top opioid prescribing specialties defined by % of opioid Rx
- Linear regression between % of opioid-related deaths and % of opioid Rx
- Linear regression between opioid-related deaths per 100K and % of opioid Rx

## Findings and Takeaways
- Overall, the number of opioid prescriptions are decreasing but opioid deaths are increasing.
- The greatest increase in percentage of opioid-related deaths is found in the 55+ population.
- States with high prescribing rates do not correspond to those with the highest death rates.

## Limitations
- Age group for opioid overdose deaths (KFF: 55+) and opioid prescriptions (Medicare: 65+) are not directly aligned
- CMS data does not include prescriptions filled through private insurance or illegally obtained opioids
- Data is delayed by three years, limiting functionality for surveillance
