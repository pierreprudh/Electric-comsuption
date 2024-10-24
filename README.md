# Individual Household Electric Power Consumption Prediction

This project focuses on predicting **Global Active Power** using the **Individual Household Electric Power Consumption Dataset**. The analysis is performed using two deep learning models: **LSTM (Long Short-Term Memory)** and **1D Convolutional Neural Networks (CNN)**. The main goal is to compare the performance of these models on time-series data.

## Dataset

The dataset is sourced from the UCI Machine Learning Repository and contains over 2 million measurements from December 2006 to November 2010, including:

- `Datetime`: Timestamp of measurement.
- `Global_active_power`: Household global active power (kilowatts).
- `Global_reactive_power`: Household global reactive power (kilowatts).
- `Voltage`: Household voltage (volts).
- `Global_intensity`: Household global intensity (amperes).
- `Sub_metering_1`, `Sub_metering_2`, `Sub_metering_3`: Energy sub-metering values.

The target variable for prediction is `Global_active_power`.

## Project Structure

```bash
├── Electric_comsumption.ipynb                      # Main Jupyter notebook for data analysis and model training
├── Electric_comsuption_graphic.ipynb               # Notebook focused on creating visuals/graphs
├── README.md                                       # Project documentation
├── model.h5                                        # Trained deep learning model (LSTM or CNN)
├── models/                                         # Directory for storing additional models
├── Rapport DL.pages                                # Report file in Pages format
├── PRUDHOMME Pierre - Electric comsuption.pdf      # PDF report summarizing findings
├── household_power_consumption.txt                 # Original dataset file
└── visuals/                                        # Directory containing generated plots and visuals
```

## Visualizing the Model
To visualize the saved model architecture, use Netron:
```bash
netron model.h5  # Visualizes the model stored in model.h5
```


## Report

The analysis and findings are documented in two reports:

- Rapport DL.pages: A Pages document with detailed analysis.
- PRUDHOMME Pierre - Electric comsuption.pdf: PDF version of the report summarizing the results.