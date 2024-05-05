# Short-Term Solar Energy Forecasting Using Spark/MLlib

This project develops a machine learning model capable of predicting short-term solar energy production using Apache Spark's MLlib and a comprehensive weather dataset. The model leverages big data processing techniques to optimize solar energy management and grid integration.

## Project Overview

- **Objective**: To create a scalable and efficient forecasting system for short-term solar energy production.
- **Methods**: Utilizes Apache Spark's distributed computing capabilities along with MLlib for machine learning.
- **Data Source**: Weather data from the Kaggle competition [Predict Energy Behavior of Prosumers](https://www.kaggle.com/competitions/predict-energy-behavior-of-prosumers/data).

## Getting Started

### Prerequisites

1. A Google account for accessing Google Colab.
2. Access to a remote cluster (DSM1) for executing comprehensive statistical analyses.
3. Ensure you have the `historical_weather_analysis.ipynb` file and the `historical_weather.csv` dataset.

### Installation

1. Clone the repository or download all required files to your local machine.
2. Install Python libraries required for the project:

   ```bash
   pip install pyspark pandas numpy matplotlib seaborn
