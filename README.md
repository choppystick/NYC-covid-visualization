# COVID-19 Data Visualization for New York City

This project provides a comprehensive set of data visualizations for COVID-19 statistics in New York City. It includes time series analyses, geographic plots, and demographic breakdowns of case rates, death rates, and hospitalization rates.

## Features

1. Time Series Visualizations:
   - Daily new cases, deaths, and hospitalizations
   - Cumulative cases, deaths, and hospitalizations
   - Interactive date range selection
   ![Figure_1](https://github.com/user-attachments/assets/9cde42c2-687d-419b-9c6f-4c0a7b12e5a6)
  ![Figure_2](https://github.com/user-attachments/assets/b015fe04-5b22-4438-a6c7-0630caf7c843)


2. Geographic Visualizations:
   - COVID-19 case rates by NYC borough
   - COVID-19 case rates by ZIP code
    ![map](https://github.com/user-attachments/assets/31cd05b4-8e11-4799-9caa-28edeadaa42e)

3. Demographic Visualizations:
   - Age group analysis of case rates, hospitalization rates, and death rates
   - Gender analysis of COVID-19 statistics

## Dependencies

This project requires the following Python libraries:

- pandas
- matplotlib
- numpy
- geopandas
- geodatasets

You can install these dependencies using pip:

```
pip install -r requirements.txt
```

## Data Sources

The data used in this project is sourced from the NYC Health Department's GitHub repository:

- [NYC Coronavirus Data](https://github.com/nychealth/coronavirus-data)

## Usage

The project is divided into three main Jupyter notebooks:

1. `covid-time-series-plots.ipynb`: Time series analysis of COVID-19 data
2. `covid-geographic-plots.ipynb`: Geographic visualizations of COVID-19 case rates
3. `covid-bar-plots.ipynb`: Demographic breakdowns and comparisons

To run the notebooks:

1. Clone this repository
2. Install the required dependencies
3. Open the Jupyter notebooks and run the cells in order

## Visualizations

### Time Series Plots

- Daily new cases, deaths, and hospitalizations over time
- Cumulative cases, deaths, and hospitalizations over time
- Interactive slider to select date ranges

### Geographic Plots

- Choropleth map of COVID-19 case rates by NYC borough
- Detailed map of COVID-19 case rates by ZIP code

### Demographic Plots

- Bar plots comparing case rates, hospitalization rates, and death rates across age groups
- Bar plots comparing COVID-19 statistics between genders

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - See [License](License.txt) for more details.

---

Note: This project uses data that is regularly updated. Make sure to pull the latest data from the NYC Health Department's GitHub repository for the most up-to-date visualizations.
