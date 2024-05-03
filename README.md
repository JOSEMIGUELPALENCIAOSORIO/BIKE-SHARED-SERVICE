# BIKE-SHARED-SERVICE
Bike Sharing Service - Analysis for Washington, DC This project analyzes the usage patterns of a bike-sharing service in Washington, DC focusing on how factors like time, weather and day type influence demand.

This dataset comes from bike rentals in the city of Washington D.C. in 2011, 2012.

-Bike_Sharing_analysis.ipynb
This is the notebook that has all of our code in it, including EDA and machine learning models.

- Streamlit.py
This is the script that you need to run to see the streamlit website.

Command to run:
streamlit run Streamlit.py

- Prediction.py 
This script receives the cleaned data and holds the processing and preparation for the model LightLGBM that we decided with the hyperparameters we found were the best. You do not need to run this script, it is called by the other script.

- bike_sharing_modify.csv 
Cleaned data to used for our model and for the Prediction.py script.
Attaching it just in case, our notebook creates it as the .csv.


