# Iris Dataset Preprocessing

This repository contains a simple data preprocessing project that converts the classic Iris dataset from raw data format (.data) to CSV format for easier analysis and manipulation.

## Project Overview

The project takes the Iris dataset (iris.data) which contains measurements of iris flowers and their species classification, and converts it into a structured CSV file with properly labeled columns.

## Files Description

- `main.py`: Python script that performs the data conversion
- `iris.data`: Original raw data file containing iris flower measurements
- `iris.csv`: Generated CSV file with labeled columns
- `requirements.txt`: List of Python dependencies

## Data Format

The dataset contains the following columns:
- C1: Petal length in cm
- C2: Petal width in cm
- C3: Petal length in cm
- C4: Petal width in cm
- Type: Iris species (setosa, versicolor, virginica)

## Dependencies

The project requires the following Python packages:
- pandas
- numpy

Install dependencies using:
```
pip install -r requirements.txt
```

## Usage

To convert the data, simply run:
```
python main.py
```

This will read the `iris.data` file and generate `iris.csv` with proper column headers.