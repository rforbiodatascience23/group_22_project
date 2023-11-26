# Project Contributors

1.  Ander Barrio Campos (s231938) - barrioskilo

2.  Dionysios Dimitreas (s232752) - DionysiosDim

3.  Erikas Mikuzis (s223164) - erikasm5

4.  Valeria Tedeschi (s231945) - Valeria0612

5.  Angeliki Vliora (s233059) - angelikivliora

# Project Description

In this project, we obtained a data set regarding diabetic and non-diabetic individuals (<https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset?select=diabetes_binary_5050split_health_indicators_BRFSS2015.csv>). This project includes 70,692 results from a survey, about different types of information, e.g high cholesterol, high blood pressure (BP), BMI, smoking status, education and income. After loading and cleaning the data in the first 2 respective files, we augmented the data set by adding variables related to the already existing ones. We created some qualitative measures to classify the individuals depending on their income, educational level, physical activity etc. The variables are described more analytically in the link above, by observing the "Data Card" of the data set.

# Data acquisition

To download the data, enter the link and press "Download". A .csv file will be downloaded to your local storage. The .csv should be imported in a "\_raw" data folder before the start of the analysis.

# Implementation

Run the 00_all.file to render all files:

-   01_load.qmd : Loading libraries and data

-   02_clean.qmd: Cleaning the data

-   03_augment.qmd: Adding new variables that will be useful in the visualization and analysis parts.

-   04_describe.qmd: Visualizing the data

-   05_analysis_1.qmd:

-   06_analysis_2.qmd:
