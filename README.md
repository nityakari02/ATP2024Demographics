# Pew Research Center's American Trends Panel W114 Demographic Dashboard

This repository hosts a Tableau dashboard to analyze survey data from Pew Research Center's American Trends Panel, specifically from Wave 114 from Sept. 13 – Sept. 18, 2022, which looks at COVID-19, scientists, and religion. The dashboard provides insights into various respondent demographics and other key metrics.

## Dashboard Features

- **Respondent Demographics**: Visualization of participant age, gender, census region, and metropolitan area.

## View the Dashboard

You can view the live Tableau dashboard directly [here](https://10ay.online.tableau.com/t/nityakarieaf2692ff4/views/ATPSurveyData/Dashboard1?:origin=card_share_link&:embed=n).

Below is a non-interactive image of the dashboard:

![Spotify 2024 Popularity Trends](https://github.com/nityakari02/ATP2024Demographics/raw/main/ATPSurveyData.png)

## Tools Used

- **Tableau Desktop**: For creating interactive visualizations and dashboards.
- **Tableau Prep**: For data cleaning and preprocessing specific to Tableau.
- **Tableau TServer**: For uploading the dashboard to be available to others.
- **R**: For data cleaning and preprocessing.
  - **dplyr**: For data manipulation.
  - **tidyr**: For data tidying.
  - **haven**: For importing and exporting data files.

## Steps to Create the Dashboard

1. **Data Collection**: Downloaded the survey data from Pew Research Center's American Trends Panel (Wave 114).
2. **Data Cleaning**:
   - Used R to clean and preprocess the data. The script is available in `ATPTableauDataCleaning.Rmd`.
   - Further cleaned and manipulated the survey data for Tableau using Tableau Prep.
3. **Data Visualization**:
   - Imported the cleaned data into Tableau Desktop.
   - Created various visualizations to represent respondent demographics and other key metrics.
   - Compiled these visualizations into a cohesive dashboard.
4. **Analysis and Presentation**:
   - Analyzed the trends and insights derived from the visualizations.

## Files Included

- `ATP Survey Data.twbx`: The Tableau Packaged Workbook file containing the dashboard.
- `ATP W114.sav`: The raw survey data from Pew Research Center's American Trends Panel.
- `ATP W114_cleaned1.csv`: The cleaned survey data.
- `ATPTableauDataCleaning.Rmd`: The R script used for cleaning and preprocessing the data.

## Getting Started

To view and interact with the dashboard locally, follow these steps:

1. Download and install [Tableau Public](https://public.tableau.com/en-us/s/download).
2. Clone this repository to your local machine using:
   ```sh
   git clone https://github.com/yourusername/ATP-Survey-Data-Analysis.git
3. Open the ATP Survey Data.twbx file in Tableau Public.

## Dataset Citation

The dataset used for this project is sourced from the Pew Research Center's American Trends Panel: https://www.pewresearch.org/dataset/american-trends-panel-wave-114/
