# air quality analysis README

This Jupyter Notebook provides a analysis to air quality predicton based on various components of so2,no2. The code includes data preprocessing, exploratory data analysis, data cleaning, and model building. Below are the steps to run this code:

## Prerequisites
1. You need to have Python installed on your system.
2. Install Jupyter Notebook and the required libraries using pip:
   ```bash
   pip install jupyter numpy pandas seaborn matplotlib scikit-learn scipy
   ```

## Steps to Run the Code
1. Clone or download the Jupyter Notebook file and the dataset ('cpcb_dly_aq_tamil_nadu-2014') to your local machine.
2. Open a terminal and navigate to the directory containing the Jupyter Notebook and the dataset.
3. Start a Jupyter Notebook session:
   ```bash
   jupyter notebook
   ```
4. In the Jupyter Notebook dashboard, open the 'ADS_phase4.ipynb' file.
5. Run the code cells in the notebook sequentially by clicking on each cell and pressing Shift + Enter.
6. You can interact with the code, view visualizations, and see analyis and average of the gases.

## Dataset Used
In this project, we used a air prediction dataset given by the ibm naan mudhalvan for analysis.
file name:'cpcb_dly_aq_tamil_nadu-2014'
## About the Dataset
The dataset consists of 11 columns, providing comprehensive information about the places and their repective so2,n02,rpsm/pm 2.5 level. this data helps us to analysis and average of the so2,no2 in different places.
The key features in the dataset include:
- Stn 
-Code 
-Sampling Date 
-State 
-City/Town/Village/Area
-Location of Monitoring Station
-Type of Location 
-SO2
-NO2 
-RSPM/PM10
-PM

We utilized this dataset to analysis amd find the average air pollution level in the different cities.


## Understanding the Code
The code consists of the following sections:
- Importing necessary libraries and reading the dataset.
- LOADING THE DATASET
-DATA EXPLORATION
-DATA VISUALIZATION
-Visualising Correlation
-calculating Averages
-calculating Averages to find average

## Data Sources
The dataset used in this code ('cpcb_dly_aq_tamil_nadu-2014.csv') is assumed to be available in the same directory as the Jupyter Notebook. This dataset contains various features of gases like so2,no2.
