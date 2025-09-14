Solar Resource Characterization, La Guajira
This repository contains the implementation of a machine learning-based framework for solar resource characterization using NASA POWER data. The project leverages Long Short-Term Memory (LSTM) networks for forecasting solar irradiance (GHI) and compares its performance with traditional models, including Linear Regression and a Naive baseline. 

To run the project, first clone the repository and install the required dependencies using pip install -r requirements.txt. Next, prepare the NASA POWER dataset (GHI, T2M, ALLSKY_KT) by uploading the CSV file when prompted. Run the preprocessing script to clean, reshape, and scale the data. Then, execute the training script to train the LSTM model and compare its performance against Linear Regression and a Naive baseline. Finally, the models' MSE values and visualizations, including predictions versus real values and model comparison charts, will be generated to assess performance.

