
# COVID-19 and Democratic Development: Data Cleaning
  
 
  
## Summary

My final project uses excel VBA tool to automate cleaning and reformatting data on country-wide COVID-19 cases and deaths. 



## Data Sources

| Data Type | Description | Website
| ---- | ---- | ---- |
| COVID-19 Cases | Global Confirmed Time Series Cases | https://github.com/CSSEGISandData/COVID-19 |
| COVID-19 Deaths | Global Time Series Deaths | https://github.com/CSSEGISandData/COVID-19 |
| Population | UN 2020 Population Estimates (millions) | http://data.un.org/ |
| Democracy | V-Dem Core Country Year | https://www.v-dem.net/data/the-v-dem-dataset/country-year-v-dem-core/ |
| Development and Wealth |Human Development Index (HDI) and Gross National Income (GNI) | https://hdr.undp.org/data-center/documentation-and-downloads |



## Video Link

[Start by watching the video summarizing this project](https://youtu.be/OqameMrOtdw)



## Documents 

The folder contains several files:

* Data_Cleaning_Model.xlsm - This is the main file to run the model and update the data
* Project_Report.pdf - This is a summary of the projects goals, results, and what I learned.
* Summary_Presentation.pptx - This presentation is used in the video to summarize the project.
* V-Dem-CY-Core-v12.csv - This is a sample version of the slimed down democracy data to load into the model. 

  
  
## Instructions

* Watch the project summary video at the link above
* Download the project file  
* Extract the files
* Open Data_Cleaning_Model.xlsm
	* This will open a welcome page where you can launch the data cleaning model. Click on the button to get started.
		> __Note__: This is a very large file that taxes the RAM on most machines. It is highly recommended that the user close other Excel files or large.
		programs before launching the macro. The COVID-19 Cases and Deaths should be updated separately from other data updates. 
	* The data updates will write to three main tabs:
		* TidyData: This includes the population, democracy, HDI, GNI, and Region data. I also assign the democracy, HDI, and GNI data to quadrants.
		* COVIDCases: This includes daily COVID-19 confirmed cases by country back to 12/31/2021 in long-format.
		* COVIDDeaths: This includes daily COVID-19 deaths by country back to 12/31/2021 in long-format.
	
Optional: Read more about the project in Project_Report.pdf, or visit the DataSources tab in the Data_Cleaning_Model.xlsm.



## Conclusion
  
This project is just the first step in my data analysis journey. The model aims to refine large data sets to allow future researchers to examine how COVID outcomes relate to
political and health factors. This project greatly improved my ability to work in VBA. However, this project also showed the shortcomings of Excel. Other
programs could have handled this load better. I am proud of what I accomplished with this tool. 

Thank you!
