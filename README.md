# COVID-19 Geographic Distribution Dataset

This repository contains data and scripts for analyzing COVID-19 geographic distribution. The dataset provides detailed information about COVID-19 cases and deaths across different countries and territories.

## Dataset

The dataset is sourced from the file coviddata.xlsx, which contains the following columns:

- *dateRep*: Date of the report (YYYY-MM-DD).
- *day, month, year*: Day, month, and year as separate columns.
- *cases*: Number of new COVID-19 cases reported.
- *deaths*: Number of new COVID-19 deaths reported.
- *countriesAndTerritories*: Name of the country or territory.
- *geoId*: Geographical ID for the country/territory.
- *countryterritoryCode*: ISO country code.
- *popData2018*: Population data for the country/territory (as of 2018).

## Project Structure

The repository is organized as follows:
## Installation

1. Clone the repository:
    bash
    git clone https://github.com/yourusername/covid-data-analysis.git
    cd covid-data-analysis
    

2. Install the required dependencies:
    bash
    pip install -r requirements.txt
    

3. Explore the dataset:
    Open the Jupyter notebook in the notebooks/ folder:
    bash
    jupyter notebook notebooks/analysis.ipynb
    

## Usage

- The data preprocessing script (preprocess_data.py) can be used to clean and prepare the dataset for analysis.
- Use the Jupyter notebook to explore visualizations, trends, and other insights from the dataset.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This dataset contains information about the COVID-19 pandemic and is used for research and educational purposes.
