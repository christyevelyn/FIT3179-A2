# Diabetes in Australia: Interactive Data Dashboard

An interactive dashboard that explores how diabetes affects Australians across states, age groups, sex and lifestyle factors, using public data from ABS and AIHW.

Live: https://christyevelyn.github.io/FIT3179-A2/

## Charts
- Map of diabetes prevalence by state
- Streamgraph of prevalence by state from 2007 to 2022
- Diverging bar chart comparing males and females by age group
- Parallel coordinates comparing lifestyle risk factors (smoking, alcohol, physical inactivity, obesity) by state
- Bubble chart of complications for Type 1 and Type 2 diabetes, with filters for complication type, age group, and sex

Every chart is interactive. Click a state, bar or point to highlight it. The bubble chart can also be zoomed and filtered with the dropdown menus.

## Findings
South Australia has the highest prevalence and the Australian Capital Territory (ACT) the lowest. Prevalence went up in every state between 2007 and 2022. Cases climb sharply from middle age, with the highest numbers between 55 and 74. Type 2 diabetes shows a stronger link to serious complications such as kidney disease.

## Data
- Australian Bureau of Statistics (ABS), National Health Survey
- Australian Institute of Health and Welfare (AIHW), diabetes data tables

The source tables were cleaned and reshaped into CSV files that each chart could read.

## Tools
- Vega-Lite
- HTML
- CSS
- JavaScript

## Files
- `index.html` dashboard page
- `*.json` chart specifications
- `data/` cleaned datasets
- `DV2_5DS.pdf` planning design sheets 
