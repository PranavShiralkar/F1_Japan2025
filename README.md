# F1 Qualifying Prediction Model for Japanese GP 2025 🏎️💨

## Overview
Welcome to the **F1 Qualifying Prediction Model**! This repository uses **machine learning** techniques to predict the **Q3 qualifying times** for the **2025 Japanese Grand Prix** based on data from recent races, along with custom performance factors for each team and driver. The predictions are generated using **linear regression** and evaluated through performance metrics like **Mean Absolute Error (MAE)** and **R² Score**.

## 🚀 Features

- **Data Fetching**: Automatically retrieves data from the first few races of the 2025 F1 season using the **FastF1** library.
- **Performance Factors**: Applies 2025-specific performance factors for each team and driver.
- **Prediction**: Predicts Q3 qualifying times for the drivers in the **2025 Japanese GP**.
- **Model Evaluation**: Evaluates the model using **Mean Absolute Error (MAE)** and **R² Score**.

## 📦 Installation

### Prerequisites

Make sure you have the following Python libraries installed to run the code:

- `fastf1`: Fetch real-time F1 race data.
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `scikit-learn`: For building and evaluating the machine learning model.

To install all dependencies, run:

```bash
pip install fastf1 pandas numpy scikit-learn
