# Python Virtual Environment Setup Guide: Complete Tutorial for Data Science Projects

A comprehensive guide for setting up and managing Python virtual environments in data science projects. Learn how to isolate dependencies, handle package management, and ensure project reproducibility across different platforms (Windows, macOS, Linux).

## Essential macOS Terminal Commands

```bash
# Check Python version
python3 --version

# Create new virtual environment
python3 -m venv venv

# Activate virtual environment
source venv/bin/activate

# Install packages from requirements.txt
pip install -r requirements.txt

# List installed packages
pip list

# Deactivate virtual environment
deactivate
```

## Understanding Virtual Environments

A virtual environment is an isolated Python environment that allows you to install and manage project-specific dependencies without interfering with system-wide Python packages. This isolation helps:

- Avoid version conflicts between different projects
- Ensure reproducibility across different development machines
- Keep your system Python installation clean
- Make project dependencies explicit and manageable

## Virtual Environment Setup

### Windows
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
venv\Scripts\activate
```

### macOS/Ubuntu
```bash
# Create virtual environment
python3 -m venv venv

# Activate virtual environment
source venv/bin/activate
```

## Dependencies

This data science project requires the following Python packages:
- pandas - For data manipulation and analysis
- numpy - For numerical computing and array operations
- openpyxl - For Excel file handling
- python-dateutil - For date parsing and handling
- pytz - For timezone calculations
- six - For Python 2 and 3 compatibility
- tzdata - For timezone database

After activating the virtual environment, install dependencies using:
```bash
pip install -r requirements.txt
```

To generate requirements.txt after installing new packages:
```bash
pip freeze > requirements.txt
```

To deactivate the virtual environment when you're done:
```bash
deactivate
```

## Usage

This project includes a data preprocessing script that converts the Iris dataset format:
```bash
python main.py
```

This will read the `iris.data` file and generate `iris.csv` with proper column headers, demonstrating practical usage of Python virtual environments in data science workflows.

## Keywords

Python virtual environment, venv, pip, package management, data science, dependencies isolation, project setup, development environment, Python packages, data preprocessing, Iris dataset, reproducible research