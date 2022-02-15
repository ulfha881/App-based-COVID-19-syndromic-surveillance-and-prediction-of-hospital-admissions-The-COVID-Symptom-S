# App-based-COVID-19-syndromic-surveillance-and-prediction-of-hospital-admissions-The-COVID-Symptom-S
Codes and example data set for Covid Symptom Study Sweden

This folder contains all codes used for the paper "App-based COVID-19 syndromic surveillance and prediction of hospital admissions: The COVID Symptom Study Sweden". The codes can be run in order in Linux from the file "0_Run.sh". The original datasets can unfortunately not be attached due to the size and confidentiality issues, but mock datasets are included which can be used when running the code, but does not represent real individuals. The code can be run using these example datasets. The Swedish example datasets are located in "/proj/sens2020559/COVID-19/OriginalData" and the UK example datasets in "/proj/sens2020559/COVID-19/OriginalData" and "/proj/sens2020559/georgioray/Split_weeks". Datasets needed to reproduce the figures and supplementary figures are located in "/proj/sens2020559/COVID-19/Figures"

All codes needed for running the analyses are located in "/proj/sens2020559/COVID-19/Codes". The bash file "0_Run.sh" runs every other code in order from beginning to end to produce all output, including sensitivity analyses. The 'sed' lines are for changing global options in the code (which is why some codes are run several times). The GitHub folder structure reproduces the folder structure used when running the codes.

The codes have been run on CentOS Linux 7 (Core).  The softwares used are R 3.6.1 and Stata/MP 15.1.
