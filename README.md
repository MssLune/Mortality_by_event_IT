# Mortality by event in Italy
Information compiled by Istat (Istituto Nazionale di Statistica) for mortality per event territory in Italy, in the field of Health and sanitation, for the years from 2003 to 2020, differentiated by male and female sex, and the initial causes of death.

## File Types
- `Mortalità per territorio di evento`: Performs a webscrapping to the [Istat page](https://www.istat.it/it/salute-e-sanita?dati), then, it uploads the information to a csv file.
- `Graphical information display`: Provides graphical reports of the information stored in the csv files. 
- `log_file` : It logs events in real time, keeping a history of them. This is useful for diagnosing problems, troubleshooting errors or tracking activities. 

## Preview

The information is obtained from the distribution of types and categories of diseases by number of deaths according to gender.

- Distribution of disease categories according to their quantity.
![distribution_by_quantity](https://github.com/MssLune/Mortality_by_event_IT/blob/main/mortality_by_disease.png?raw=true)

- Distribution of disease categories by number of deaths by gender.
![distribution_by_gender](https://github.com/MssLune/Mortality_by_event_IT/blob/main/mortality_by_disease_gender.png?raw=true)
