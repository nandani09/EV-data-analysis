# EV-data-analysis
Overview
This repository contains a data analysis project focused on Electric Vehicle (EV) data. The analysis explores various aspects of the EV market, including population growth, sales trends, and geographical distribution of electric vehicles. The dataset used includes various information about EV models, market penetration, and other related statistics.

Objectives
Analyze the growth of the electric vehicle population over time.
Visualize the trends in EV sales and adoption.
Explore the relationship between various factors affecting EV adoption.
Predict future trends based on current data (if applicable).
Dataset
The dataset used for this analysis is a CSV file containing information about electric vehicle models, their sales, and other relevant details. The key columns include:

Model: The name of the electric vehicle model.
Year: The year of data collection.
Sales: The number of units sold.
Region: The region or country where the vehicles were sold.
EV Population: The total number of electric vehicles in that year.
You can find the dataset in the Electric_Vehicle_Population_Data.csv file.

Files in the Repository
EV data analysis.ipynb: The main Jupyter Notebook containing the analysis, data cleaning, visualizations, and insights.
Electric_Vehicle_Population_Data.csv: The dataset used in the analysis.
requirements.txt: A list of Python dependencies required to run the analysis (if applicable).
Installation
To run the analysis locally, clone this repository and install the required dependencies.

Clone the repository:

bash
Copy code
git clone https://github.com/nandani09/EV-data-analysis.git
Navigate to the project directory:

bash
Copy code
cd EV-data-analysis
Install the necessary Python libraries:

bash
Copy code
pip install -r requirements.txt
Or manually install the libraries used in the notebook (such as pandas, numpy, matplotlib, seaborn, etc.):

bash
Copy code
pip install pandas numpy matplotlib seaborn
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook EV\ data\ analysis.ipynb
Usage
The EV data analysis.ipynb notebook contains all the steps to clean the data, perform exploratory data analysis (EDA), visualize the trends, and generate insights. Run each cell to understand the trends in EV adoption and sales over time.

Key Analysis Sections in the Notebook:
Data Cleaning: Handling missing values, renaming columns, and ensuring the data is in the correct format.
Exploratory Data Analysis (EDA): Analyzing the data to understand trends in the number of electric vehicles, sales, and population.
Visualizations: Generating plots using matplotlib and seaborn to illustrate key trends, such as sales over time, regional distributions, and growth patterns.
Insights and Predictions: Drawing conclusions based on the data and making predictions for future EV trends (if applicable
