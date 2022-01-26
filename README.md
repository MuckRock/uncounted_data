# Documenting COVID-19 and MuckRock's Uncounted Project
This repository contains data and findings used in Documenting COVID-19's Uncounted project with the USA TODAY network, found here: [Uncounted: Inaccurate death certificates across the country hide the true toll of COVID-19](https://www.usatoday.com/in-depth/news/nation/2021/12/22/covid-deaths-obscured-inaccurate-death-certificates/8899157002/), which was published in December 2021.

## Overview
The data in the repository come from three sources
1. [The WONDER database from the U.S. Centers for Disease Control and Prevention](https://wonder.cdc.gov/) (last updated Dec.4)
2. 

[Along with this reporting recipe,](https://www.muckrock.com/news/archives/2022/jan/06/how-to-use-uncounted-cdc-data/), the data in the repository can be combined to make sense of counties with high amounts of "unexplained excess deaths" during the pandemic, deaths that point toward COVID-19 death undercounts. The reporting recipe covers the origins of death records, why death data is important, and how to use it. 



## Table of Contents
1. Data
2. Data Dictionaries

## What useful things will you find in the data folder?
1. [Excess mortality modeling by state](data/excess_mortality_modeling), includes two datasets, one modeled by the CDC and one by a team at Boston University [led by Andrew Stokes, an assistant professor of global health](https://www.bu.edu/articles/2022/underreporting-covid-19-deaths/?utm_campaign=social_experts&utm_source=twitter&utm_medium=photo&utm_content=research_publichealth)
2. Several [breakdowns of deaths by state from 2018 through 2022](data/race_ethnicity_cause_place_breakdowns), including by race/ethnicity, cause and setting. We've found that each of these distinctions changes the quality of death investigation a person receives
3. [Vaccination rates by state](data/vaccinations), which can be cross-referenced to other datasets found in this repository
4. [Your state's medicolegal death investigation system](data/coroner_and_medical_examiner_survey) - whether a coroner, mixed coroner/medical examiner or state medical examiner system
5. A Department of Justice survey of all medical examiner and coroner offices in the country, conducted in 2018 and published in 2021, provides [the resources, personnel, tools, and caseload of your local death investigation system](data/coroner_and_medical_examiner_survey). We've included the whole survey along with a paired down version in a separate .csv file to make the data more digestible and ready to use

## Methodology and Caveats
1. Our investigation focused on underreporting COVID deaths, but not all excess deaths are COVID deaths. We cover this in our [Uncounted "how to" guide](https://www.muckrock.com/news/archives/2022/jan/06/how-to-use-uncounted-cdc-data/);
>The term “excess death” refers to the estimate of how many more people died in a given time period and region than expected. The expected number of deaths is derived through statistical modeling and typically accounts for changing mortality trends. Epidemiologists and demographers have used excess mortality to measure natural and non-natural disasters, such as during Hurricane Maria and opioid overdose deaths.

Measuring excess deaths helps determine how many more people are dying than a normal, pre-pandemic year, and the rest of the data in this repository serves to explain what those people are dying of, and possibly, why.

2. CDC WONDER data for 2021 and 2022 are provisional and not yet final. This means some numbers are still subject to change. If any numbers raise a red flag for you though, you should check the numbers out on the ground, by asking local practitioners or by contacting the [National Center for Healthcare Statistics directly](https://www.cdc.gov/nchs/index.htm).

## Questions and Feedback
The Documenting COVID-19 project can be reached at dillon@muckrock.com, betsy@muckrock.com and derek@muckrock.com.
