# US Accident Analysis

This repository contains a Jupyter Notebook for analyzing traffic accident data in the United States. The analysis explores patterns, trends, and factors contributing to accidents using a dataset of reported incidents.

## Features

- **Data Cleaning**: Prepares raw accident data for analysis by handling missing values and formatting inconsistencies.
- **Exploratory Data Analysis (EDA)**: Visualizes accident trends by:
  - Time (hour, day, month, year)
  - Location (states, cities)
  - Weather and environmental conditions
- **Insights**: Identifies factors influencing accident severity, frequency, and distribution.

## Requirements

The following Python libraries are required:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Install dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Nireey/Accident_Analysis_US.git
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook us_accident_analysis.ipynb
   ```
4. Run the cells step-by-step to execute the analysis.

## Data Source

The dataset used in this project is sourced from [US Accident Data on Kaggle](https://www.kaggle.com). Ensure that you have the dataset in the appropriate directory before running the notebook.
### Note

- Since the dataset was too large to work with directly, it was randomly split into smaller subsets to make the analysis more manageable. Care was taken to ensure that the data was chosen evenly to maintain its representativeness.
- The `us-states.json` file used in this project was downloaded from [PublicaMundi's MappingAPI repository](https://github.com/PublicaMundi/MappingAPI/tree/master/data/geojson).

## Outputs

- Visualizations and tables that summarize accident trends.
- Insights into accident-prone locations, times, and conditions.

## Contribution

Feel free to open issues or submit pull requests if you'd like to improve this project.
