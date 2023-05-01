# README


## Project Description

BU Sustainability supports the transformation of Boston University’s planning, operations, and culture toward a sustainable and equitable future.They have pulled multiple spreadsheets with data from their 3rd party vendor Contelligent and our waste vendor Casella. Contelligent provides PSI fullness monitoring of our compactors. The client has provided detailed data sets from each monitor, overall data, temperature data, and waste generation spreadsheet by data from Casella.  The analysis of these datasets will inform BU Sustainability how they can potentially improve where to store waste if there are adverse weather effects.

## Introduction
The aim of this project is to support BU's Sustainability department in their efforts to transform the university's planning, operations, and culture towards a sustainable and equitable future. Specifically, the project seeks to investigate the correlation between weather conditions and waste production and storage. To accomplish this, we will analyze detailed data sets from various sources, including monitors, overall data, temperature data, and waste generation spreadsheets from Casella.

Our analysis of these datasets will provide valuable insights to BU Sustainability, enabling them to identify potential areas for waste storage improvement in the event of adverse weather conditions. Through a comprehensive analysis of the data provided by both the Sustainability Department and third-party vendors, the project aims to deepen our understanding of how external factors impact the waste collection process.

Our ultimate goal is to offer insights that will help to enhance the waste collection process and support BU's sustainability objectives.


## Running the code
Our team were focusing on different part of works so what you need is using Jupyter notebook or Google Colab to select each different part of work and make sure you select the correct path for the data in your machine. The code are noted with details comments and you don't need to install extra libraries yourself since it will be installed when needed during running the codes.

# Teams work

## Zeqi Wang: 
The research I focused on was finding out if there is a relationship between temperature and the compressor's psi value. The dataset I was using was the ‘readings_device.#####.csv’. The time frame of the data record was from 2021-07-01 to 2022-10-02, and 24 compressor machines were located at the BU campus (Charles, Fenway, and MED). I performed Correlation analysis and Linear regression prediction for psi values and temperature for each compressor. To run the code in my section, simply go to my folder, select the desired Deliverable folder, then change the path for csv files based on your machine. 

## Timur Zhunussov:
I have addressed additional data like inconsistencies in the temperature data by merging readings from different locations and comparing them with historical data from NCEI CDO, resulting in nearly identical data. Additionally, I tried to distinguish between compactions and waste pickups, although interpreting the data was challenging due to its density. By applying smoothing techniques and analyzing the PSI values, we gained insights into waste pickup patterns. Finally, have tested three models: Linear Regression, Decision Trees, and SVM, to predict temperature. While Linear Regression and SVM showed low or no correlation, Decision Trees performed better, but the possibility of overfitting must be considered.

## Baicheng Fang:
Firstly, I use the extracted data from BU_Daily_Weights_FY22 to examine the correlation between waste production and temperature. In some certain cases, there is some correlation but far from fitting to a model.
Obviously I need to do more feature engineering to improve the model’s performance, so I try to add more features to do multiple linear regression to further analyze the correlation between temperature and other parameters.
The domain knowledge of waste production yields many factors. Apart from temperature, we suppose pressure is also important. So I use the psi reading data preprocessed by Zeqi. I examine with OLS and simple MSE. I choose 5 out of all given sites for fitting tests, BU #38 Life Sciences 20 has the best performance. I will test the rest in the immediate future. The code has been uploaded to the project's git repository under my branch.

## Akshad Ramnath: