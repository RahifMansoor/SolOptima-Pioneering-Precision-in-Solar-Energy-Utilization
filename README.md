### README for Solar Energy Prediction Project

#### Project Overview
Welcome to the Solar Energy Prediction Project, also known as "SolSight: Precision Predictions for Solar Efficiency." This project leverages machine learning (ML) techniques to predict solar power consumption, aiding companies in optimizing their energy usage and advancing sustainability goals. Through detailed Jupyter notebooks, we explore, analyze, and predict solar energy consumption using various factors such as weather conditions, operational data, and time metrics.

#### Getting Started

To dive into our analysis and models, follow these steps to set up the project on your local machine.

**Prerequisites:**
- Python 3.6 or later
- Jupyter Notebook or JupyterLab
- Relevant Python packages: pandas, numpy, matplotlib, seaborn, keras, scikit-learn

Navigate through the directory structure in the Jupyter interface to open and run the notebooks. They are designed to be run sequentially:

1. `Model_Power_Consumption.ipynb` - For initial data loading, cleaning, and exploratory analysis.
2. `Predict_Power_Consumption.ipynb` - Contains the model building, training, and evaluation process.

#### Notebooks Summary

- **Data Preparation and Analysis**: This notebook guides you through the data preparation steps, including cleaning and exploratory data analysis (EDA), setting the stage for effective model development.
- **Model Development**: Focused on building and evaluating machine learning models to predict solar power consumption. This includes linear regression models and LSTM networks for time series forecasting.

#### Data Sources and File Descriptions

The Solar Energy Prediction Project utilizes data from multiple sources, focusing on solar power consumption, weather conditions, and operational data such as employee counts. Understanding the origin and structure of these data files is crucial for replicating our analysis and leveraging the insights for practical applications.

**Data Sources:**
- The primary data for solar power consumption and related features are sourced from publicly available datasets and proprietary data shared by partner organizations committed to advancing renewable energy research.
- Weather data, including temperature and sunlight hours, is obtained from the OpenWeatherMap API, ensuring accurate and timely environmental information.

**File Descriptions:**
- `SolarGeneration_Data.xlsx`: This comprehensive Excel file contains multiple sheets, each representing different aspects of solar power data and related variables.
  - **Sheet 1 ("Daily Energy Consumption")**: Daily records of solar power consumption, temperature, and the number of operational employees.
  - **Sheet 2 ("Hourly Energy Consumption")**: Hourly details of energy consumption, offering a granular view of power usage throughout the day.
  - **Sheet 3 ("Weather Data")**: Contains historical weather data, crucial for understanding the impact of environmental conditions on solar power generation and consumption.
  - **Sheet 4 ("Employee Count")**: Daily and hourly records of employee presence, providing insights into the operational aspects influencing energy usage.

- `dailyEnergyWithFeatures.xlsx`: A derived dataset prepared during the analysis, combining solar power consumption with weather data and employee counts on a daily basis, ready for machine learning modeling.

**Utilizing the Data:**
To replicate our analysis or build upon it, download these files and place them in a directory accessible to the Jupyter notebooks. The notebooks contain code for loading and processing these files, ensuring a seamless start to your exploration.

