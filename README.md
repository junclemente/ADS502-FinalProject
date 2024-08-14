# ADS502-FinalProject

This project is part of the ADS-502 course in the Applied Data Science Program at the University of San Diego.

--Project Status: **Completed**

- Define Purpose - **Completed**
- Obtain Data - **Completed**
- Explore and Clean Data - **Completed**
- Determine data mining task - **Completed**
  - Use EDA to determine features that are correlated to the target
- Choose data mining methods - **Completed**
  - Decision Tree
  - Random Forest
  - Naïve Bayes
  - Logistic Regression
  - k-Nearest Neigbor
  - Neural Network
- Apply methods and select final model - **Completed**
- Evaluate performance - **N/A**

## Installation

Clone repository to your PC.
Ensure your environment includes the libraries as listed under 'Technologies'.

If you have [anaconda](anaconda.com) installed, you can create an environment using the `mambaML.yml` file in the `environments` folder.

Within a conda environment, create a new environment:

```
conda env create -f <path/to/mambaML.yml>
```

## Project Intro/Objective

The main purpose of this project is to develop a machine learning model to accurately predict the severity of an accident based on specific features.

## Contributors

- [Matt Ammirati](https://github.com/Mammirati15)
- [Amayrani Balbuena](https://github.com/amayranib)
- [Jun Clemente](https://github.com/junclemente)

## Methods Used

- Decision Tree
- k-Nearest Neighbor
- Logrithmic Regression
- Naïve Bayes
- Neural Network
- Random Forest

## Technologies

- python 3.10.\*
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- jupyter
- statsmodels
- pydotplus
- pip
- scikeras[tensorflow]
- tensorflow
- imblearn

## Project Description

This project focuses on the predictive modeling of road traffic accident severity. The primary goal is to accurately predict the severity of accidents, focusing on those resulting in serious injuries, to improve emergency response deployment and reduce the potential for fatalities.

The data "Road Traffic Accidents" was acquired from Kaggle.com, which has 8210 entries and 32 features plus the target variable. Through exploratory data analysis, we selected nine (9) features that we believe are the variables that contribute the most to severity of accidents. Our final dataset includes 8210 entries.

One of the challenges that we've encountered is that large class imbalance among the three classifications of Accident_severity.

### Data Dictionary

| **Variable Name**             | **Description**                                       | **Type**    | **Possible Values / Range**                                                                                                                                                                                                                                                                                                                                                                    |
| ----------------------------- | ----------------------------------------------------- | ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Area_accident_occurred`      | The area where the accident took place.               | Categorical | Residential areas, Office areas, Recreational areas, Industrial areas, Other, Church areas, Market areas, Unknown, Rural village areas, Outside rural areas, Hospital areas, School areas, Rural village areas, Office areas                                                                                                                                                                   |
| `Types_of_Junction`           | The type of junction where the accident occurred.     | Categorical | No junction, Y Shape, Crossing, O Shape, Other, Unknown, T Shape, X Shape                                                                                                                                                                                                                                                                                                                      |
| `Light_conditions`            | The light condition during the accident.              | Categorical | Daylight, Darkness lights lit, Darkness - no lighting, Darkness - lights unlit                                                                                                                                                                                                                                                                                                                 |
| `Number_of_vehicles_involved` | The number of vehicles involved in the accident.      | Discrete    | 1 to 7                                                                                                                                                                                                                                                                                                                                                                                         |
| `Number_of_casualties`        | The number of casualties as a result of the accident. | Discrete    | 1 to 8                                                                                                                                                                                                                                                                                                                                                                                         |
| `Cause_of_accident`           | The primary cause of the accident.                    | Categorical | Moving Backward, Overtaking, Changing lane to the left, Changing lane to the right, Overloading, Other, No priority to vehicle, No priority to pedestrian, No distancing, Getting off the vehicle improperly, Improper parking, Overspeed, Driving carelessly, Driving at high speed, Driving to the left, Unknown, Overturning, Turnover, Driving under the influence of drugs, Drunk driving |
| `Day_of_week`                 | The day of the week when the accident occurred.       | Categorical | Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday                                                                                                                                                                                                                                                                                                                                 |
| `Sex_of_driver`               | The gender of the driver involved in the accident.    | Categorical | Male, Female, Unknown                                                                                                                                                                                                                                                                                                                                                                          |
| `Age_band_of_driver`          | The age band of the driver involved in the accident.  | Categorical | 18-30, 31-50, Under 18, Over 51, Unknown                                                                                                                                                                                                                                                                                                                                                       |
| `Accident_severity`           | The severity of the accident.                         | Categorical | Slight Injury, Serious Injury, Fatal injury                                                                                                                                                                                                                                                                                                                                                    |

(OpenAI, 2024)

Dataset: Road Traffic Accidents (Gharsalli, 2024)

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

Gharsalli, S. (2024). Road Traffic Accidents [Dataset]. Kaggle. [https://www.kaggle.com/competitions/road-traffic-accidents](https://www.kaggle.com/competitions/road-traffic-accidents)

OpenAI. (2024). ChatGPT (August 2024 version) [AI Model Output]. OpenAI. [https://chat.openai.com/](https://chat.openai.com/)
