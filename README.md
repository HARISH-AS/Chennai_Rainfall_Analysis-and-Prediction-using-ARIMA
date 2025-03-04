Sustainable Water Development in Chennai

Exploratory Data Analysis (EDA) and Predictive Modeling


Overview

Water scarcity is a significant issue in Chennai due to rapid urbanization, climate change, and poor water management. This project employs Exploratory Data Analysis (EDA), regression models, and machine learning techniques (ARIMA) to analyze historical data and predict future water availability trends.

Key Features

Data Analysis: Visualization of water availability trends using graphs, charts, and maps.

Predictive Modeling: ARIMA model for forecasting rainfall and reservoir levels.

Water Quality Analysis: Assessing parameters like pH, hardness, and total dissolved solids.

Sustainable Water Management Strategies: Policy recommendations based on findings.

Dataset

The dataset includes historical data on:

Rainfall patterns (2010-2021)

Reservoir storage levels (2004-2021)

Groundwater availability

Sewage treatment capacity

Water quality indicators

Installation & Requirements

To run the analysis, install the required Python packages:

pip install pandas numpy matplotlib seaborn statsmodels

Running the Project

Clone the repository:

git clone https://github.com/your-repo-name.git
cd your-repo-name

Run the Jupyter notebook or Python script:

python analysis.py

Check the results for EDA and predictive analysis.

Project Structure

|-- dataset/               # Contains all raw and preprocessed datasets
|-- src/                   # Source code for data analysis and modeling
|-- notebooks/             # Jupyter notebooks for EDA and modeling
|-- results/               # Generated reports and graphs
|-- README.md              # Project documentation (this file)

Results & Findings

Rainfall Patterns: Most rainfall occurs from October to December, with peaks in November.

Reservoir Levels: Chembarambakkam and Redhills reservoirs contribute ~75% of Chennai's water supply.

Water Quality: High variation in pH, hardness, and total dissolved solids across sources.

Predictive Modeling: Forecasts for 2024 indicate potential stress on water availability if current trends continue.

Future Improvements

Incorporating real-time data for improved model accuracy.

Expanding the scope to include wastewater management and groundwater recharge.

Applying deep learning models for enhanced forecasting.


License

This project is licensed under the MIT License.

Developed as part of the Winter 2022-2023 CSE3040 Exploratory Data Analytics Course at VIT Chennai.

