Impact of COVID-19 Variants on Cost-Effectiveness across age groups: A modeling study
---
## Description of the data and file structure
The epidemiological data from February 2021 to December 2022 were acquired from the Korea Disease Control and Prevention Agency (KDCA) [17]. We excluded the imported cases, focusing on the characteristics of locally transmitted cases, to analyzed the number of daily reported cases, deaths of COVID-19 in Republic of Korea, summarized in Supplementary Table 1-2. The age-specific data of both confirmed cases and vaccinated number of individuals were classified into five age groups as 0-19, 20-34, 35-49, 50-64, 65+ years. The demographic composition of the Korea residents was obtained for February 2021 from Korean Statistical Information Service (KOSIS) [18]. The number of completed second dose of the COVID-19 vaccine was obtained from KDCA. We do not consider the specific types of vaccines. To generate the daily number of vaccine doses, we assumed that they were vaccinated equivalently for a week. The population size is based on the 2021 population.

## Code/Software

The code was designed in the matlab 2022 b version. The order of execution is
1. Fit_run2.m file in the fitting folder
2. ModelRun2.m file in the fitting_checking folder
3. Senario.m file in the senario folder
4. The bf_senario.m file in the bf_senario folder
5. Codes for Figure are summarized in figure folder
