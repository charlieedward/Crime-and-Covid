# Analysis of Crime and Covid-19 in Los Angeles

In 2020, Los Angeles recorded more than 300 murders for the first time in more than a decade. More and more homeless appeared surrounding the community and the number of killings began spiking shortly after the onset of the pandemic, and thus threaten students safety. 
Thus, the project aims to use the open data and Firebase as the database to help users get more familiar with crime and the patterns of suspect behaviors; besides, if there’s relation between covid-19 and crime rate, I hope to use the pandemic data to predict the crime amount.

## Data Sources
The open data used in the project:
- Crime_Data_from_2010_to_2019.csv
- LA_County_Covid19_tests_date_table.csv

After Preprocessing:
- covid_modified.csv
- crime_data_modified.csv

## Four Notebooks
- upload_data.py.ipynb -> let user to upload the raw data to firebase
- User_Input_or_Delete_Data.py.ipynb  -> let users manipulate the data on firebase via UI
- Overview Analysis.ipynb -> show the overall findings
- Customized Analysis_Ipywidgets.ipynb -> let users search and do the visualization they want