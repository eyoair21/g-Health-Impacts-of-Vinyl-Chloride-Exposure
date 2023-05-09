# Health Impact Assessment of Hazardous Chemical Exposure in Train Derailments
This GitHub repository contains the code and data used in our study to assess the health impact of hazardous chemical exposure following train derailment incidents, with a focus on the East Palestine train derailment accident. Our aim is to provide valuable information for first responders, decision-makers, stakeholders, and researchers involved in emergency response, risk assessment, and the development of robust models for assessing the health impact of hazardous chemical exposure.

## Overview
We developed a dataset using a quantitative risk assessment model and employed three machine learning models, including:
Linear Regression
Ridge Regression
Lasso Regression
These models were used to analyze the potential health impacts associated with hazardous chemical exposure (vinyl chloride) to the local population if they had stayed in the region during the accident and the release of toxic chemicals. In addition in building quantitative model certian variables were assumed as constant, this needs future improvement.

## Methodology
We used the Gaussian plume model and linear evaporation model to estimate exposure concentrations and the subsequent cancer risks and hazard quotients. The primary objective of this study was to identify the most effective model for assessing potential health risks associated with vinyl chloride exposure.

## Evaluation Metrics
The models were evaluated using the following performance metrics:

Root Mean Square Error (RMSE)
Coefficient of Determination (CD)
Mean Absolute Error (MAE)
These metrics help in determining the effectiveness and accuracy of the models used.

## Repository Contents
data/: Contains the dataset used for the study, which is based on the East Palestine train derailment accident.
models/: Contains the implementation of the three machine learning models (Linear Regression, Ridge Regression, and Lasso Regression).
evaluation/: Contains the code to evaluate the models using the performance metrics (RMSE, CD, and MAE).
results/: Contains the results and insights derived from the study, which can be helpful for decision-makers, stakeholders, and researchers.
README.md: The file you are currently reading.

## Dependencies
To run the code in this repository, you will need to have the following libraries installed:

Python 3.x
NumPy
pandas
scikit-learn

## Contributing
If you wish to contribute to this project, please open an issue or submit a pull request with the changes or additions you'd like to make.

## License
This project is licensed under the UNT License. 
## Acknowledgements

