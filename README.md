# Kansas-Clean-Energy-Cost-Forecast

## Project Overview
This project I am estimating electricity demand in Kansas over the next five years and estimating the cost of meeting that demand only using wind and solar power. I am using historical data to build a linear regression model that forecasts demand over the next five years. This will help stakeholders see what the electricity demand is in Kansas for the next five years, how much it would cost to replace that demand with renewable energy, and then evaluate the trade-offs involved in future  clean energy projects.

## Data Sources
U.S Energy Information Administration:
https://www.eia.gov/electricity/data.php
Annual Technology Baseline - National Laboratory of the Rockies:
https://atb.nlr.gov/electricity/2025/data?utm_source=chatgpt.com

## Environment Setup
Clone the repository and navigate into the project folder:
git clone https://github.com/CCCKBrant/Kansas-Clean-Energy-Cost-Forecast.git cd Kansas-Clean-Energy-Cost-Forecast

Install required python packages:

pip install -r requirements.txt

Jupyter Notebooks are stored in "notebooks/" directory

Open "notebooks/01_data_exploration.ipynb"

## Project Structure
Kansas-Clean-Energy-Cost-Forecast/ ├── data/ │ ├── raw/ │ └── processed/ ├── notebooks/ ├── src/ ├── reports/ ├── requirements.txt └── README.md

