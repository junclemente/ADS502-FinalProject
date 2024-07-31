# ADS502-FinalProject

This project is part of the ADS-502 course in the Applied Data Science Program at the University of San Diego.

_--Project Status: In Progress_

- Define Purpose - _In Progress_
- Obtain Data - **Completed**
- Explore and Clean Data - **Completed**
- Determine data mining task - **Completed**
  - Use EDA to determine features that are correlated to the target
- Choose data mining methods - _In Progress_
  - Decision Tree
  - Random Forest
  - Naive Bayes
  - Logistic Regression
  - k-Nearest Neigbor
  - Neural Network
- Apply methods and select final model
- Evaluate performance

## Installation

To use this project, clone the repo on your device:
<steps to clone repo>

Within a conda environment, create a new environment:

```
conda env create -f <path/to/mambaML.yml>
```

## Project Intro/Objective

The main purpose of this project is _<enter reason>_. \_Describe the goals of the project
and potential impacts. Mention the needs/applications of your project clearly.
Limit to one/two short paragraphs(s).

The main purpose of this project is to develop a machine learning model to accurately predict the severity of an accident based on specific features.

## Contributors

- [Matt Ammirati](https://github.com/Mammirati15)
- [Amayrani Balbuena](https://github.com/amayranib)
- [Jun Clemente](https://github.com/junclemente)

## Methods Used

## Technologies

- ChatGPT was used to write the data dictionary.

## Project Description

_Discuss the details of project overview. Description your selected dataset, such as data source, number of variables, size of dataset, etc. Include data dictionary if, available. Provide questions and hypothesis that you are exploring. What specific data analysis, visualization, and modeling work are you using to solve the problem? What roadblocks and challenges are you facing? etc_

### Data Dictionary

7. Day_of_week
8. Age_band_of_driver:
9. Sex_of_driver
10. Area_accident_occured
11. Types_of_Junction
12. Light_conditions
13. Number_of_vehicles_involved: The number of vehicles involved in the accident.
14. Number_of_casualties: The number of casualties involved in the accident.
15. Cause_of_accident: The primary cause or contributing factor of the accident.
16. Accident_severity (target): The severity of the accident.


### Data Dictionary (Updated)

| **Variable Name**            | **Description**                                                                                  | **Type**      | **Possible Values / Range**                                                                 |
|------------------------------|--------------------------------------------------------------------------------------------------|---------------|------------------------------------------------------------------------------------------------|
| `Area_accident_occurred`      | The area where the accident took place.                                                          | Categorical   | Residential areas, Office areas, Recreational areas, Industrial areas, Other                                                      |
| `Types_of_Junction`           | The type of junction where the accident occurred.                                                | Categorical   | No junction, Y Shape, Crossing                                                                 |
| `Light_conditions`            | The light condition during the accident.                                                        | Categorical   | Daylight, Darkness - lights lit                                                                 |
| `Number_of_vehicles_involved` | The number of vehicles involved in the accident.                                                | Discrete      | 1 to 7                                                                                         |
| `Number_of_casualties`        | The number of casualties as a result of the accident.                                           | Discrete      | 1 to 8                                                                                         |
| `Cause_of_accident`           | The primary cause of the accident.                                                              | Categorical   | Moving Backward, Overtaking, Changing lane to the left, Changing lane to the right, Overloading, No priority to vehicle, No priority to pedestrian, No distancing, Other |
| `Day_of_week`                 | The day of the week when the accident occurred.                                                 | Categorical   | Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday                                 |
| `Sex_of_driver`               | The gender of the driver involved in the accident.                                              | Categorical   | Male, Female                                                                                    |
| `Age_band_of_driver`          | The age band of the driver involved in the accident.                                            | Categorical   | 18-30, 31-50, 51-70                                                                             |
| `Accident_severity`           | The severity of the accident.                                                                   | Categorical   | Slight Injury, Serious Injury                                                                  |


Dataset: [Sonia Gharsalli. (2024). Road Traffic Accidents. Kaggle. https://www.kaggle.com/competitions/road-traffic-accidents](https://www.kaggle.com/competitions/road-traffic-accidents)

## License

MIT License

Copyright (c) 2024 Matt Ammirati, Amayrani Balbuena, Jun Clemente

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgements
