# Solar Vigilantes: spotting outliers in PV generation data

This project focuses on exploring weather data and generation data from a photovoltaic power plant. The original datasets were obtained from Kaggle, specifically from plant 2 .csv files [here](https://www.kaggle.com/datasets/anikannal/solar-power-generation-data/data). 

The main goal of this project is to identify outliers in the solar power generation data. These outliers may indicate potential issues such as malfunctioning inverters, failures, the need for maintenance or cleaning, or even a complete shutdown of certain components.

To identify outliers, the analysis focuses on employing linear regression and analyzing its residuals. The goal is to scrutinize these residuals, aiming to detect instances where the actual power output significantly diverges from the anticipated values based on the provided irradiation levels.
The analysis currently relies solely on linear regression and its residuals. The notebook utilizes this approach to pinpoint instances where observed power output deviates significantly from expected values based on irradiation levels. However, future updates to the notebook will introduce additional non-supervised methods to enhance outlier detection capabilities.
