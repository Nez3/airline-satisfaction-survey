
# Airlines Satisfaction Survey Analysis

![logo](https://github.com/Nez3/airline-satisfaction-survey/blob/main/airline_gif.gif?raw=true)


## Dataset Summary

* Number of rows: 129880
* Number of columns: 25
* Dataset link: [airlines_passengar_dataset.csv](https://github.com/Nez3/airline-satisfaction-survey/blob/85d0b905253959711d31a95f7ad8aa2f676fcdfe/airline_passenger_satisfaction.csv)


*Another dataset called date.xlsx is used in order to get additional information about date like longdate, short-date, month, weekday, etc. The date dataset can be found [here.](https://github.com/Nez3/airline-satisfaction-survey/blob/main/Date_table.xlsx)*
## Project Objective
The objective of this project is to analyze the airlines passengar dataset for an airline. It aims to find common issues faced by the customer with the airline.

The dataset consist ratings given by customers on various performance parameters of the airline. Some of the parameters include: Ease of booking, check-in service, Seat Comfort, Cleanliness, In-flight service, etc. (check out airlines_passengar_dataset.csv for more information)

## How To Use

To clone and run this project, you'll need [Git](https://git-scm.com) and [Power BI](https://powerbi.microsoft.com/en-us/downloads/)

From your command line:

```bash
# Clone this repository
$ git clone https://github.com/Nez3/airline-satisfaction-survey.git

# Go into the repository
$ cd airline-satisfaction-survey

```

## Download

You can [download](https://powerbi.microsoft.com/en-us/downloads/) the latest installable version of Power Bi for Windows, macOS and Linux.

## Power BI
[Power BI](https://learn.microsoft.com/en-us/power-bi/) is a robust business intelligence tool developed by Microsoft, facilitating data analysis and visualization. Users can connect to various data sources, transform raw data into meaningful insights through interactive reports, dashboards, and data visualizations. It aids in decision-making processes, enabling organizations to derive actionable intelligence from their data effortlessly.


## Steps taken to build visualizations

[1] Loaded airlines_passengar_dataset.csv and date.csv in Power BI

[2] Created relationship between both the tables by joining on date columns

[3] Transformed both the tables by filtering out only those dates which are required from the date table

[4] Created measures for defining calculations in the DAX model

[5] Story building: analyzed data and recognized three umbrella topics on which analysis can be done

[6] Visualizations: Three main topics were explored using visualizations (Demographics, Net Promoter Score, User Experience)

* For detailed implementation process, check out the [Power BI steps document]()

## Visualizations

* **Demographic Analysis**:
  Understanding satisfaction levels among different customer types, travel purposes, classes, genders, and age groups can help tailor services, marketing strategies, and improve overall customer experience, thereby enhancing loyalty and profitability.

  ![Demographics](https://github.com/Nez3/airline-satisfaction-survey/blob/main/visualizations/demographic_analysis.png?raw=true)

* **Net Promoter Score**: Net Promoter Score (NPS) enables airlines to gauge customer loyalty and satisfaction over time. By comparing NPS scores between 2021 and 2022 across various evaluation parameters, airlines can pinpoint areas for improvement, prioritize enhancements, and track progress in enhancing overall customer experience, fostering loyalty, and driving business growth.

  ![NPS](https://github.com/Nez3/airline-satisfaction-survey/blob/main/visualizations/NPS_analysis.png?raw=true)

* Customer Experience:




## Contact:
> Email: [nehab1@arizona.edu](mailto:nehab1@arizona.edu) &nbsp;&middot;&nbsp;
> GitHub [@Nez3](https://github.com/Nez3) &nbsp;&middot;&nbsp;
> LinkedIn [Neha_Bharambe](https://www.linkedin.com/in/neha-bharambe21/)

