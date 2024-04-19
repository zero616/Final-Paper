# Predicting Canadian residents’ consumption amount through house prices

## Overview

This project analyzes Data analysis of NHPI and Consumption of Canada from 2000 to 2009

## File Structure
```
Homeless_Death_Analysis
|   .gitignore
|   .RData
|   .Rhistory
|   Empirical Analysis.Rproj
|   LICENSE
|   README.md
|   
+---inputs  
|   +---data
|   |       plane_data.csv
|   |       raw_data_NHPI.csv
|   |       raw_data_cost.csv
|   +---literature
|   |       Alexander-ProjectOfStateLevel.pdf
|   |       
|   +---llm
|   |       usage.txt
|   |       
|   \---sketches
|           dataset.pdf
|           graph.pdf
|           
+---outputs
|   +---data
|   |       analysis_data.csv
|   |       cleaned_data_NHPI.csv
|   |       cleaned_data_cost.csv
|   \---paper
|           datasheet_template.pdf
|           datasheet_template.qmd
|           paper.pdf
|           paper.qmd
|           references.bib
|           
\---scripts
        00-simulate_data.R
        01-download_data.R
        02-data_cleaning.R
        03-test_data.R
        04-model.R
        05-styer.R
```

## Data Source

The data set used in this analysis was obtained from the Open Gov of Canada

## Installation

To run the analysis, you need R and the following R packages:

-   **ggplot2** [@R-ggplot2]

-   **dplyr** [@R-dplyr]

-   **janitor** [@R-janitor]

-   **rmarkdown** [@R-rmarkdown]

-   **knitr** [@R-knitr] 

-   **lubridate** [@R-lubridate]

-   **rstanarm** [@R-rstanarm]

-   **arrow**[@R-arrow]

-   **caret**[@R-caret]
-   tidyverse

# Statement on LLM Usage

This project does not make use of any Language Model (LLM) in its analysis, code, or documentation.
