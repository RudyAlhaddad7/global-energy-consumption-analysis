# Global Energy Consumption Analysis

## Project Overview
This project explores global energy consumption data to uncover trends, patterns, and insights. The goal is to analyze how energy use changes across countries and years, and to visualize findings clearly.

## Dataset
- **Filename:** `data/global_energy_consumption.csv`
- **Description:** Open-source dataset containing global energy consumption statistics by country and year.

- **Filename:** `data/annual_co2_emissions_country.csv`
- **Description:** Annual CO₂ emissions per year by country, sourced from Our World in Data.

- **Filename:** `data/dataGDP.csv`
- **Description:** GDP data by country and year, sourced from the World Bank combining GDP(USD) - GDP Growth - Population Total.

## Limitations

- The dataset contains multiple entries per country-year, which may represent duplicates or subcomponents of total consumption.
- Aggregating by sum can overcount; median can undercount.
- This affects the reliability of country-level total calculations.
- Trends and correlations are more trustworthy than absolute totals.

## Project Structure
```
data/        # Contains the dataset CSV file
notebooks/   # Jupyter notebooks for exploration and analysis
README.md    # Project summary and instructions
.gitignore   # Files/folders to ignore in git
```

## How to Run
1. Clone the repo.
2. Open `notebooks/eda.ipynb` in VSCode/Jupyter.
3. Run the cells to explore the data!


## How to Read

Open `notebooks/eda.ipynb` directly from GitHub browser 

## Credits
Made by Rudy Alhaddad 898742.
