# Project Name
> Linear Reression modelling for bike users


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To determine:
 - Which variables are significant in predicting the demand for shared bikes.
 - How well those variables describe the bike demands
- The business is to earn revenue by encourage sharing of bikes and supplying sufficient bikes to satisfy demand 
- Business Goal
 - Model the demand for shared bikes with the available independent variables
 - Target model usage:
    - Understand how exactly the demands vary with different features
    - Manipulate business strategy to meet demand levels and cater to cusomer satisfaction
    - Understand the demand dynamics of a new market
- Data Source:
 - Location : America
 - Meteorological survey
 - People's styles

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The following steps were performed:
    - Data visualization
    - Data preparation
    - Testing multiple approaches to build the multiple linear regression model
- Final Model
    - users = 0.1805 +  yr * 0.2363 + workingday * 0.0561 + atemp * 0.4135 + season_spring*(-0.1057) + season_winter * 0.0792 + mnth_Jan*(-0.0458) + mnth_May * 0.0368 + mnth_Sep * 0.0739 + mnth_Nov * (-0.0564) + mnth_Dec * (-0.0485) + weekday_Sat*0.0655 + weathersit_2.0 *(-0.0819) +  weathersit_3.0 * (-0.3091 )

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- The implementation was done in Python 3.8.10 with the following libraries
- scikit-learn  - version  1.0.2
- scipy - version 1.8.0
- seaborn - version 0.11.2
- kaleido - version 0.2.1
- matplotlib - version 3.5.1
- numpy - version 1.22.2
- pandas - version 1.4.0
- plotly - version 5.6.0
- statsmodels - version 0.13.2
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was possible due to the efforts and guidance of UPGRAD team



## Contact
Created by [@ssatyendras] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->