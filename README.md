# EDA_SP500
# S&P 500 App with Stock Closing Prices

This Streamlit app retrieves the list of S&P 500 companies from Wikipedia and displays the corresponding stock closing prices for selected sectors. Users can choose sectors from the sidebar, view company data, and download the data in CSV format.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Libraries Used](#libraries-used)
- [Data Source](#data-source)
- [License](#license)

## Introduction

The S&P 500 App is a Streamlit application that leverages web scraping and financial data fetching to provide users with information about S&P 500 companies and their year-to-date closing prices. Users can interact with the app by selecting specific sectors, viewing company data, and downloading the data for further analysis.

## Features

- Display a list of S&P 500 companies grouped by sectors.
- Allow users to select sectors of interest.
- Display detailed information about companies in the selected sector.
- Enable users to download the displayed data in CSV format.
- Fetch year-to-date stock closing prices for selected companies using the yfinance library.
- Visualize stock closing prices for the selected companies.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. Install the required Python libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the Streamlit app using the following command:

```bash
streamlit run app.py
