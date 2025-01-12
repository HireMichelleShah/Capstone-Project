Project Overview

This project focuses on analyzing SpaceX Falcon 9 launch data to uncover insights into mission success factors and predict the likelihood of successful first-stage landings. The analysis covers data collection, wrangling, exploratory data analysis (EDA), interactive visualizations, and predictive modeling using machine learning techniques.

Project Structure

Data Collection:

Utilized the SpaceX REST API to gather launch data, including rocket type, payload mass, launch site, and landing outcomes.

Performed web scraping on Wikipedia using BeautifulSoup to collect supplementary launch data.

Data Wrangling:

Handled missing values and cleaned datasets for analysis.

Merged data from different sources and engineered relevant features.

Exploratory Data Analysis (EDA):

Conducted data visualization using scatter plots, bar charts, and SQL queries to explore relationships between flight variables and mission outcomes.

Interactive Visual Analytics:

Created interactive maps using Folium to visualize launch sites and outcomes.

Developed dashboards using Plotly Dash for dynamic data exploration.

Predictive Analysis:

Built and tuned classification models (Logistic Regression, SVM, Decision Tree, KNN) to predict the success of Falcon 9 first-stage landings.

Repository Contents

edadataviz.ipynb - Exploratory Data Analysis with visualizations.

jupyter-labs-eda-sql-coursera_sqllite.ipynb - SQL-based data exploration.

jupyter-labs-spacex-data-collection-api.ipynb - SpaceX API data collection notebook.

jupyter-labs-webscraping.ipynb - Web scraping of Wikipedia data.

lab_jupyter_launch_site_location.ipynb - Launch site location analysis.

labs-jupyter-spacex-Data wrangling.ipynb - Data cleaning and wrangling.

SpaceX_Machine Learning Prediction_Part_5.ipynb - Machine learning model development and evaluation.
