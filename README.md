# Automated Cryptocurrency Data Analysis Project 

## Overview
This project is a Python-based automated cryptocurrency data analysis tool. It connects to the CoinMarketCap API to retrieve real-time data, performs continuous data collection, and provides dynamic visualizations of cryptocurrency price trends over different time intervals.

## Features
- **API Integration:**
  - Utilizes the CoinMarketCap API to fetch the latest cryptocurrency data.
  - Connection handled using the `requests` library.

- **Automated Data Collection:**
  - Implements a function (`api_runner()`) for continuous data collection at one-minute intervals.
  - Data stored in a CSV file (`api2.csv`) for historical analysis.

- **Data Analysis and Visualization:**
  - Pandas used for efficient data manipulation.
  - Seaborn and Matplotlib employed for dynamic visualization of percent changes in cryptocurrency prices.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/YaseenTheAnalyst/Automate-API-Extraction)https://github.com/YaseenTheAnalyst/Automate-API-Extraction
   cd Automate-API-Extraction

## Requirements
- Python 3.x
- Jupyter Notebooks

## Contributions
Contributions are welcome! If you find a bug or have suggestions for improvement, feel free to open an issue or submit a pull request.

## Acknowledgments
__Thanks to CoinMarketCap for providing the API used in this project.__
__Inspiration drawn from the Python and data analysis communities.__

Happy coding!
