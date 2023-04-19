# Maternity Foundation Data Imputation Project

## Overview

This project for the 1st Semester of the AAU Business data science master, aims to utilize data imputation techniques to address the issue of missing data for the Maternity Foundation's Safe Delivery App. The app provides knowledge and training to assist women with various maternal health ailments. The missing data stems from user-provided information, such as geographic location, professional background, and incomplete data entries. We seek to complete this objective using tools and techniques learned in our 1st semester in Data Science.

## Overview

Addressing the missing data issue is crucial, as it can impact business operations and decision-making. Reducing the size of the dataset by imputing missing data will also improve the performance of the Safe Delivery App on mobile devices in countries like India and Ethiopia, where users may have limited storage capacity and processing power.

## Dataset

The data in this project comes from the Safe Delivery App users in India and Ethiopia.

## Methodology

* Exploratory Data Analysis (EDA): Perform an EDA to reveal key findings and figures relevant to stakeholders.

* Principal Component Analysis (PCA): Conduct a PCA on the most significant dimensions related to users' interactions with the Safe Delivery App, the duration of these interactions, and their results.

* Data Imputation: Impute missing data based on the dimensions identified in the PCA, and showcase the code used to achieve this.

## Reflections and Future Work

- Reflect on the project's results, methodology, and potential areas for improvement.
- Discuss potential future research based on the findings.
- Share reflections on teamwork collaboration using the Agile project management theory, and the experience of delegating the project into the phases of envision,  speculate, explore, adapt, and closing.
- Provide a conclusion for the project.

## Getting Started

To get started with this project, clone the repository and follow the instructions in the Jupyter notebooks provided.

git clone https://github.com/yourusername/maternity-foundation-data-imputation.git


## Dependencies

- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

## Appendix:
The list of files to be submitted for the project submission is the following:

● Data_cleaning.ipynb - This jupyter lab document contains the preprocessing for the
project and data preparation.

● Feature_importance.ipynb - This jupyter lab document contains our feature importance.

● Imputation_pipe_test.ipynb - This jupyter lab document contains our main data

imputation, as well the output that we will base our conclusion primarily upon.
● Imputation_prelim_EDA.ipynb - This jupyter lab document contains EDA.

● Lat-Lon_reverse.ipynb - This jupyter lab document uses the user data latitude and
longitude to find the district of the user and states.

● Requirements.txt - This word text document contains the !pip installs that are required to
run the various jupyter lab documents.

● Project_Read_Me.txt - This word document contains instructions how to run the various
jupyter lab documents, and in which order.


## License

This project is licensed under the MIT License.
