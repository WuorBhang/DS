# DS Economic Data Analysis with FRED API

## Overview

This project analyzes economic data from the Federal Reserve Economic Data (FRED) using Python, focusing on unemployment rates and labor force participation across U.S. states.

## Features

Fetches S&P 500 data and creates visualization
Analyzes state-level unemployment rates
Compares unemployment rates with labor force participation rates
Creates interactive visualizations using Plotly and Matplotlib

## Requirements

### Dependencies

- fredapi
- pandas
- matplotlib
- plotly
- python-dotenv

### Installation

```bash
pip install fredapi pandas matplotlib plotly python-dotenv
```

For Windows users, you can also run these commands individually:

```cmd
pip install fredapi
pip install pandas
pip install matplotlib
pip install plotly
pip install python-dotenv
```

## Setup

### 1. Fork the repository

#### 2. Clone the repository

#### 3. Install dependencies

```bash
pip install fredapi pandas matplotlib plotly python-dotenv
```

## Create a .env file in the project root

```bash
FRED_API_KEY=your_api_key_here
```

Get your FRED API key from [FRED API Key page](https://fred.stlouisfed.org/docs/api/api_key.html)

## Usage

The notebook contains several sections:

### 1. FRED Object Creation

    Initializes connection to FRED API
    Loads environment variables

### 2. S&P 500 Data

    Fetches and plots S&P 500 index data

### 3. State Unemployment Analysis

    Retrieves unemployment data for all states
    Creates visualizations of unemployment trends

### 4. Labor Force Participation

    Compares unemployment rates with participation rates
    Generates multi-state comparison plots

## Data Sources

All data is sourced from FRED (Federal Reserve Economic Data):

-State unemployment rates (Seasonally Adjusted)
-Labor force participation rates
-S&P 500 index values

## Visualizations

The notebook generates several visualizations:

S&P 500 time series plot
State-by-state unemployment rates
Combined unemployment and participation rate plots for each state

## License

MIT License

## Contributing

1. Fork the repository
2. Clone the repository
3. Create your feature branch
4. Make changes
5. Commit your changes
6. Push to the branch
7. Open a Pull Request
