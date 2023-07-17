## Exploratory Data Analysis
Project Goal
The goal of this project was to clean, analyze, and visualize data from the "MEPS HC-228 2021 Full Year Population Characteristics" dataset. The project aimed to identify trends between diabetes and certain key demographic characteristics, focusing on age, sex, race, ethnicity, employment status, education, and country of birth.
Dataset Documentation
The dataset's documentation can be found here. It provides information about the validity and sample size for the population, along with key codes and other pertinent information regarding the data collected.
## Background on the Dataset
The dataset is a public use file containing information collected on a nationally representative sample of the civilian noninstitutionalized population of the United States for the calendar year 2021. It includes data from multiple rounds of the Medical Expenditure Panel Survey (MEPS). The dataset contains variables related to survey administration, demographics, person-level conditions, health status, disability days, quality of care, health care delays due to COVID-19, COVID-19 vaccinations, Social Determinants of Health (SDOH), employment, and health insurance.
## Key Findings from the Exploratory Data Analysis:
    * Demographic Factors and Diabetes:
    * The dataset included variables related to demographics such as age, sex, race, ethnicity, employment status, education, and country of birth.
    * The goal was to investigate the correlation between demographic factors, especially race, and the occurrence of diabetes.
    * A hypothesis was proposed that certain racial groups may have a higher prevalence of diabetes.
    * The dataset was filtered to select key variables of interest.
    * Diabetes Prevalence by Country of Birth:
    * Among the individuals with diabetes in the dataset, approximately 79.26% were born in the USA, suggesting a higher chance of being diagnosed with diabetes for US-born individuals.
    * A small number of individuals (7) refused to answer the survey question about their country of birth.
    * Diabetes Prevalence by Gender:
    * Among the individuals with diabetes, there were 1,518 men and 1,747 women.
    * The average age of diabetes diagnosis was 48 for men and 47 for women, indicating no significant disparity between genders.
    * Diabetes Prevalence by Race:
    * The dataset provided information on different racial groups: Hispanic, Non-Hispanic White, Non-Hispanic Black, Non-Hispanic Asian, and Non-Hispanic Other.
        * The counts of individuals with diabetes were as follows:
        * Hispanic: 703
        * Non-Hispanic White: 1,629
        * Non-Hispanic Black: 654
        * Non-Hispanic Asian: 143
        * Non-Hispanic Other: 136
    * Visualizations were created to display the diabetes prevalence for each racial group.
    * Diabetes Prevalence Adjusted for Sample Size:
    * To account for differences in the sample sizes of each racial group, the counts of individuals with diabetes were divided by the total count for each race.
        * The resulting percentages were as follows:
        * Hispanic: 10%
        * Non-Hispanic White: 11%
        * Non-Hispanic Black: 16%
        * Non-Hispanic Asian: 10%
        * Non-Hispanic Other: 13%
    * These percentages provide a more accurate comparison of diabetes prevalence among different racial groups.
    * Age of Diabetes Diagnosis by Race:
    * The average age of diabetes diagnosis varied among racial groups.
    * White and Asian individuals tended to receive a diabetes diagnosis at a later age compared to Black, Hispanic, and other racial groups.
    * Hispanic and other racial groups tended to receive a diabetes diagnosis around the age of 43-44. This finding suggests that cultural foods may have a lesser influence on diabetes development when compared to the potential impact of a US diet. It implies that non-US born Hispanics, who are more inclined to cherish their cultural cuisine rather than indulge in American dishes, may demonstrate a potentially lower diabetes risk.
    * Age of Diabetes Diagnosis by Country of Origin:
    * Among US-born Hispanics, the average age of diabetes diagnosis was 44.
    * Among Hispanics not born in the USA, the average age of diabetes diagnosis was 49.
    * This suggests that US-born Hispanics receive a diabetes diagnosis at an earlier age compared to Hispanics not born in the USA.
    * Employment Status and Diabetes:
    * Individuals who have worked that reported having diabetes: 1321
    * Individuals who have never worked that reported having diabetes: 457
    * These results may be caused by other variables such as age, as the survey contains data from children who are unable to work. So, this may only suggest that working adults are more likely to have a diabetes diagnosis which isn’t particularly surprising. 
    * Further analysis can be conducted to explore the correlation between employment status and diabetes diagnosis.
## Resume Skills Practiced
The project allowed for the application and practice of the following skills:
* R programming
* Data cleaning
* Data visualization
## Packages Used
The following packages were utilized for this project:
* dplyr
* tidyverse
* ggplot2
* psych
* sqldf
* utils
## Data Set
This dataset is a fairly large size and originally consisted of 28,336 entries and 990 total columns. For this project, the following columns were selected and focused on:
* BORNUSA: Person born in the US
* DIABAGED: Age of diagnosis for diabetes
* DIABDX_M18: Diabetes diagnosis
* DOBYY: Date of birth (year)
* DUID: Panel number + encrypted DU identifier
* DUPERSID: Person ID (DUID + PID)
* EDUCYR: Years of education when first entered MEPS
* EVRWRK: Ever worked for pay in life as of 12/31/21
* HIDEG: Highest degree when first entered MEPS
* HRWG31X: Hourly wage RD 3/1 CMJ (IMP)
* HRWG42X: Hourly wage RD 4/2 CMJ (IMP)
* HRWG53X: Hourly wage RD 5/3 CMJ (IMP)
* PERWT21P: Use file person weight, 2021
* RACEAX: Asian among races reported (edited/imputed)
* RACEBX: Black among races reported (edited/imputed)
* RACETHX: Race/ethnicity (edited/imputed)
* RACEV1X: Race (edited/imputed)
* RACEV2X: Race (edited/imputed)
* RACEWX: White among races reported (edited/imputed)
## R Cleaning and Analyzing Steps
The detailed cleaning and data analysis steps, along with the corresponding R code, can be found in the following documents:
* [Cleaning and Analysis Steps](https://docs.google.com/document/d/1SGZrEwqvfDTv7yttrEemYgg99dBqZ0B_OSGYWLr1dT0/edit?usp=sharing)
* [R Code](https://docs.google.com/document/d/15BplmBAyTHKT6KwwRu3E7gwmPLX2NbtLbPlDK3PlSx0/edit?usp=sharing)
## Tableau Dashboard and Report (Work in Progress)
A Tableau dashboard and a short report based on the insights discovered are currently being developed. Updates will be provided once they are available.
For now the link the my Tableau Public Profile can be found [here](https://public.tableau.com/app/profile/joanne.st.remy)
