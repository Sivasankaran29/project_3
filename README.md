# Data Normalization and Flattening

## Overview

This project involves normalizing and flattening nested data within a DataFrame. The provided code processes an Excel file containing various nested structures and converts them into a more structured and accessible format. The final output can be saved as either an Excel or CSV file.

## Features

- **Safe Literal Evaluation**: Converts string representations of dictionaries and lists to actual Python objects.
- **Recursive Dictionary Flattening**: Converts nested dictionaries and lists into a flat structure with combined keys.
- **Data Normalization**: Applies the above techniques to specific columns in a DataFrame, making nested data more accessible.

## Prerequisites

- Python 3.x
- `pandas` library
- `ast` library (part of Python standard library)

## Installation

Install the required Python library using pip:

```bash
pip install pandas

# Data Column Selection and Export

## Overview

This project involves selecting specific columns from an Excel file and exporting the filtered data to a new CSV file. The provided script processes the data to retain only the desired columns and saves the result in a CSV format.

## Features

- **Column Selection**: Choose specific columns from the DataFrame to keep.
- **CSV Export**: Save the filtered DataFrame to a new CSV file.

## Prerequisites

- Python 3.x
- `pandas` library

## Installation

Install the required Python library using pip:

```bash
pip install pandas
# Data Cleaning and Export

## Overview

This project involves cleaning a CSV file by removing rows with null values and exporting the cleaned data to a new CSV file. The provided script processes the data to ensure that only complete rows are retained.

## Features

- **Remove Null Values**: Deletes rows that contain any null values.
- **CSV Export**: Save the cleaned DataFrame to a new CSV file.

## Prerequisites

- Python 3.x
- `pandas` library

## Installation

Install the required Python library using pip:

```bash
pip install pandas
# Column Renaming and Export

## Overview

This project involves renaming columns in a CSV file according to a specified dictionary and exporting the updated data to a new CSV file. The provided script processes the data to update column names for better readability and saves the result in a new file.

## Features

- **Rename Columns**: Change column names based on a predefined dictionary.
- **CSV Export**: Save the DataFrame with updated column names to a new CSV file.

## Prerequisites

- Python 3.x
- `pandas` library

## Installation

Install the required Python library using pip:

```bash
pip install pandas
# Data Cleaning and Conversion

## Overview

This project involves cleaning and converting columns in a CSV file to ensure data consistency and accuracy. The provided script processes various columns to standardize their formats, remove invalid entries, and save the cleaned data to a new CSV file.

## Features

- **Convert Column Names**: Replace spaces in column names with underscores.
- **Data Cleaning**: Standardize and clean columns, including:
  - Converting columns to appropriate data types.
  - Extracting and normalizing values (e.g., years, prices).
  - Handling missing or invalid data.
- **CSV Export**: Save the cleaned DataFrame to a new CSV file.

## Prerequisites

- Python 3.x
- `pandas` library

## Installation

Install the required Python library using pip:

```bash
pip install pandas
# Data Cleaning and Normalization

## Overview

This project involves further cleaning and normalization of a CSV file containing vehicle data. The script performs tasks such as removing duplicate rows, handling missing values, normalizing column names, and cleaning text data.

## Features

- **Remove Duplicates**: Eliminate duplicate rows from the DataFrame.
- **Handle Missing Values**: 
  - Fill missing values in specific columns with median or a placeholder.
  - Fill other missing values with 'Unknown'.
- **Normalize Column Names**: 
  - Strip whitespace, convert to lowercase, and replace spaces with underscores.
- **Remove Accents and Special Characters**: Clean text columns to remove accents and special characters.
- **Convert Data Types**: Convert columns to appropriate data types (e.g., float, integer).

## Prerequisites

- Python 3.x
- `pandas` library

## Installation

Install the required Python library using pip:

```bash
pip install pandas
# CSV Data Combination

## Overview

This script combines multiple CSV files into a single DataFrame. Each file is associated with a city name, which is added as a new column to identify the source of the data. The combined data is then saved to a new CSV file.

## Features

- **Load CSV Files**: Reads multiple CSV files into individual DataFrames.
- **Add City Column**: Adds a 'city' column to each DataFrame to indicate the source city.
- **Combine DataFrames**: Concatenates all DataFrames into a single DataFrame.
- **Save Combined Data**: Exports the combined DataFrame to a new CSV file.

## Prerequisites

- Python 3.x
- `pandas` library

## Installation

Install the required Python library using pip:

```bash
pip install pandas
# Random Forest Regression Model for Car Price Prediction

## Overview

This project involves building and evaluating a Random Forest Regression model to predict car prices based on various features. The script performs data preprocessing, hyperparameter tuning, model training, evaluation, and saving of the model and scaler.

## Features

- **Data Loading**: Loads a CSV file containing car data.
- **Data Preparation**: Selects relevant features, handles missing values, and encodes categorical variables.
- **Model Training**: Trains a Random Forest Regressor using hyperparameter tuning with RandomizedSearchCV.
- **Model Evaluation**: Evaluates model performance using Mean Squared Error (MSE) and R-squared (R²).
- **Cross-Validation**: Provides additional evaluation using cross-validation scores.
- **Model Saving**: Saves the trained model, scaler, and feature columns for future use.

## Dependencies

- Python 3.x
- `pandas`
- `scikit-learn`
- `joblib`
- `scipy`

Install the required Python libraries using pip:

```bash
pip install pandas scikit-learn joblib scipy
# Car Price Prediction Streamlit App

## Overview

This Streamlit application allows users to predict car prices based on various features such as fuel type, body type, company, model, and more. The application uses a pre-trained Random Forest Regressor model for predictions. Users can input car details through a web interface, and the app will provide an estimated price.

## Features

- **Interactive Web Interface**: Users can enter car details through dropdowns, sliders, and text inputs.
- **Real-Time Predictions**: The app provides a predicted price based on user inputs.
- **Model and Scaler Integration**: Utilizes a pre-trained Random Forest Regressor model and StandardScaler for prediction.

## Dependencies

- Python 3.x
- `streamlit`
- `pandas`
- `joblib`

Install the required Python libraries using pip:

```bash
pip install streamlit pandas joblib
