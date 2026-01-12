<html>
<h1>🏠 NYC Housing Sales Price Prediction - Data Analysis Project with Python </h1>

<body>
<h2>📌 Project Overview</h2>
<p>This project analyzes a combined dataset from both the NYC Citywide Rolling Sales dataset and NYC PLUTO (Primary Land Use Tax Lot Output) dataset, that includes the actual property sales prices as well as the properties' related characteristics such as lot area, building area, land use and so on.

The goal of the project is to clean the dataset, create visualizations to present the relationship between variables, and eventually build an optimal machine learning model trying to predict the sales price of NYC properties based on their inherent building characteristics

Data Visualization on Tableau: https://public.tableau.com/app/profile/xiao.huang3780/viz/NYCHousingDataVisualization/Dashboard1?publish=yes

</p>

<h2>🎯 Project Goals</h2>
<p>The main objectives of the project include:<br>
<ul>
<li>Clean the dataset by filling in NaNs, removing duplicates, processing categorical variables stored as numeric variables, and transforming skewed values using <b><em>Python</em></b>.</li>
<li>Create data visualization to examine how <b><em>NYC property sales price</b></em> related to different building characteristics such as building age, land use, and so on.</li>
<li>Build machine learning models to find the most accurate models to <b><em>predict NYC property sales prices</b></em> based on the building characteristics.</li>
<li>Export the cleaned data set and build interactive data viz dashboards using <b><em>Tableau</b></em>.</li>
</ul>

<h2>📊 Dataset</h2>
<p>
Source: NYC Citywide Rolling Sales dataset + PLUTO building dataset<br>
Link: https://www.kaggle.com/datasets/ishank2005/nyc-housing-prices-csv/data<br>
Dataset Overview: This dataset contains property sales transactions across the five NYC boroughs, combining transaction records with building and lot characteristics for predictive modeling and exploratory analysis.<br>
Key Variables:
<ul>
  <li>Sale Price (<code>sale_price</code>)</li>
  <li>Location (<code>borough_x</code>, <code>zip_code</code>, <code>latitude</code>, <code>longitude</code>)</li>
  <li>Building Characteristics (<code>yearbuilt</code>, <code>building_age</code>, <code>bldgarea</code>, <code>lotarea</code>)</li>
  <li>Property Type & Land Use (<code>landuse</code>, <code>bldgclass</code>)</li>
</ul>
</p>

<h2>🛠️ Project Methods</h2>
<p>
Tools: Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)<br>
Key Methods:
<ul>
  <li>Cleaned and prepared NYC housing sales data (missing values, duplicates, and data type fixes)</li>
  <li>Applied log transformation to <code>sale_price</code> to reduce skewness and improve model performance</li>
  <li>Encoded categorical variables (borough and land use) using one-hot encoding for machine learning models</li>
  <li>Performed exploratory data analysis (EDA) using distribution plots and correlation heatmaps</li>
  <li>Built and evaluated regression models (Linear Regression, Random Forest, Gradient Boosting) using R², RMSE, and MAE</li>
  <li>Generated feature importance outputs to identify key drivers of NYC housing prices</li>
</ul>
</p>

<h2>📈 Outcomes</h2>
<p>
Key Results:
<ul>
  <li>Developed a complete end-to-end regression workflow to predict NYC housing sale prices using structured property and location features</li>
  <li>Established a baseline Linear Regression model (R² ≈ 0.20) and demonstrated performance gains using non-linear models</li>
  <li>Achieved improved predictive accuracy with Random Forest (R² ≈ 0.44) and Gradient Boosting (R² ≈ 0.34)</li>
  <li>Produced a feature importance table to identify the strongest predictors of housing prices (e.g., building area, borough, land use, and building age)</li>
</ul>

</p>
 
</body>

</html>
