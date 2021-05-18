# COVID-19 PREDICTION TOOL #
-------------------------------------------------------------------------------------------------------------------------------------
### K Nearest-Neighbours classifier for COVID-19, with 92.3% accuracy ###

To classify a person, create a cell at the bottom of the notebook and run classify(<information list>)
The information list is a list containing 0s and 1s, corresponding to No/ Yes, in the following order:

cough || fever || sore_throat || shortness_of_breath || head_ache || age_60_and_above || sex(1: Male, 0: Female) 

For Eg: if a female under the age of 60 has cough, sore throat, and head ache, they would be classified using: 
classify([1, 0, 1, 0, 1, 0, 0])

-------------------------------------------------------------------------------------------------------------------------------------
         
Sources: CSV file taken from https://github.com/nshomron/covidpred/blob/master/data/corona_tested_individuals_ver_006.english.csv.zip 
         CSV file originally sourced from: https://data.gov.il/dataset/covid-19 
