
# COVID-19 Global Data Tracker

This project is a Python-based data analysis and visualization tool for tracking and analyzing global COVID-19 data. It uses publicly available data from [Our World in Data](https://covid.ourworldindata.org/) to provide insights into COVID-19 cases, deaths, and vaccination progress across different countries.

## Features

- **Data Download**: Automatically downloads the latest COVID-19 dataset in CSV format.
- **Data Cleaning**: Handles missing values and filters data for selected countries.
- **Exploratory Data Analysis (EDA)**:
  - Visualizes total COVID-19 cases and deaths over time for selected countries.
  - Analyzes vaccination progress over time.
- **Global Choropleth Map**: Displays total COVID-19 cases by country using an interactive map.
- **Key Findings**: Summarizes key insights from the analysis.

## Technologies Used

- **Python Libraries**:
  - `requests`: For downloading the dataset.
  - `pandas`: For data manipulation and analysis.
  - `matplotlib` and `seaborn`: For data visualization.
  - `plotly.express`: For creating an interactive choropleth map.

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. Install the required libraries using:
   ```bash
   pip install pandas matplotlib seaborn plotly requests
   ```

3. **Run the Notebook**:
   Open the Jupyter Notebook file (`COVID-19 Global Data Tracker project!.ipynb`) in Jupyter Notebook or JupyterLab and execute the cells sequentially.

## Visualizations

- **Line Plots**:
  - Total COVID-19 cases over time for selected countries.
  - Total COVID-19 deaths over time for selected countries.
  - Vaccination progress over time for selected countries.
- **Choropleth Map**:
  - Interactive map showing total COVID-19 cases by country.

## Key Findings

- Total COVID-19 cases, deaths, and vaccinations vary significantly across countries.
- India shows a rapid increase in vaccination progress over time.
- The United States has the highest total cases and deaths among the selected countries.
- Kenya has a slower vaccination progress compared to India and the United States.

## Dataset

The dataset is sourced from [Our World in Data](https://covid.ourworldindata.org/data/owid-covid-data.csv). It includes global COVID-19 data such as cases, deaths, and vaccinations.

## Future Improvements

- Add more countries for analysis.
- Include additional metrics such as testing rates and hospitalizations.
- Automate data updates and visualizations.

## License

This project is for educational purposes and uses publicly available data. Please ensure compliance with the data source's terms of use.

## Acknowledgments

- [Our World in Data](https://ourworldindata.org/) for providing the COVID-19 dataset.
- Python community for the amazing libraries used in this project.
