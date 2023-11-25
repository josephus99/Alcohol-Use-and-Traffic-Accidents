# Alcohol Use and Traffic Accidents Analysis

## Introduction

This notebook explores the correlation between alcohol consumption and traffic fatalities in the United States. The analysis spans the years 2019 to 2021, incorporating data from various sources.

## Installation

Before you begin, ensure you have met the following requirements:

- Python 3.8.10 (You can download it from [Python Official Website](https://www.python.org/))
- Git (You can download it from [Git Official Website](https://git-scm.com/downloads))

### Steps:

1. Open a terminal or command prompt.
2. Navigate to your desired directory where you want to clone the project.
3. Run the following command to clone the GitHub repository:
```
git clone https://github.com/josephus99/Alcohol-Use-and-Traffic-Accidents.git
```
4. Navigate to the Project Directory:
```
cd Alcohol-Use-and-Traffic-Accidents
```
5. Install virtualenv if not already installed:
```
python3 -m pip install virtualenv
```
6. Create a new virtual environment:
```
python3 -m venv myenv
```
7. Activate the virtual environment:
- On Windows:
  ```
  .\myenv\Scripts\activate
  ```
- On Unix or MacOS:
  ```
  source myenv/bin/activate
  ```
8. Install the required packages from the requirements.txt file:
```
pip install -r requirements.txt
```
9. Run the command to set up your environment in Jupyter Notebook:
```
python -m ipykernel install --user --name=myenv
```
10. Open Jupyter Notebook:
```
jupyter notebook
```

11. In your web browser, go to Jupyter Notebook[Jupyer Notebook](http://localhost:8888/tree)

12. Click on clean_and_process_data.ipynb. In the Jupyter Notebook navigation bar, select Kernel -> Change Kernel -> myenv. Then click on Cell in the navigation bar and select Run All.

13. After all the cells are run, go back to the Jupyter Notebook and click on `data_analysis_project.ipynb`. Run all cells here as well.

## Project Structure

- `clean_and_process_data.ipynb`: Cleans and preprocesses the data, and then merges it.
- `data_analysis_project.ipynb`: Main Colab notebook containing data analysis.
- `datasets/`: Folder containing the datasets used in the analysis.

## Data Sources

- [Alcohol consumption data](https://www.niaaa.nih.gov/sites/default/files/surveillance-report120.pdf#page=15)
- [Highway Traffic deaths Excel file](https://www-fars.nhtsa.dot.gov/States/StatesAlcohol.aspx)
- [States geographic information](https://hub.arcgis.com/datasets/1b02c87f62d24508970dc1a6df80c98e/explore)

## Data Dictionary

- State (string): The name of the U.S. state. Data Type: String
- Year_2019 (int): Highway Traffic fatalities in the year 2019
- Year_2020 (int): Highway Traffic fatalities in the year 2020
- Year_2021 (int): Highway Traffic fatalities in the year 2021

## Project Goals

- Visualize Alcohol consumption and Highway traffic deaths by State
- Investigate the relationship between alcohol consumption and Highway traffic deaths

## Setup Instructions

- Run all the cells in `clean_and_process_data.ipynb` to preprocess data
- Run the cells in `data_analysis_project.ipynb` in order to perform the data analysis.

## Data Integration

- Combined and analyzed state-level data on alcohol use in the United States.
- Integrated this information with datasets on alcohol-related traffic accidents by state.

## Correlation Analysis

- Applied statistical methods to identify correlations between alcohol use metrics and the incidence of traffic accidents at the state level.
- Visualized these relationships through charts and graphs to enhance interpretability.

## Data Visualization

- Utilized Matplotlib to create visually appealing representations of the analysis results.
- Present state-specific patterns and trends that emerge from the correlation analysis.

## Reproducibility and Documentation

- Developed a well-documented and reproducible data analysis program using Jupyter Notebook.
- Provided clear documentation of data cleaning steps, analysis methodologies, and visualization processes.

## Results

- Key insights from the analysis.
- Visualizations illustrating the correlation between alcohol consumption and traffic fatalities.

## Acknowledgements

- The Data was obtained from the US National Highway Traffic Safety Administration
- The data about US fatalities were obtained from the National Institute on Alcohol Abuse and Alcoholism

## Why This Analysis?

Understanding the intricate relationship between alcohol use and traffic accidents at the national level is crucial for crafting effective public safety strategies. By examining state-level data, this project aims to contribute nuanced insights that may guide targeted interventions and policy decisions aimed at improving road safety across the United States.

## Summary Findings

This analysis explored the relationship between alcohol consumption and traffic fatalities in the United States from 2019 to 2021. The investigation revealed a notable negative correlation between the average alcohol consumption per state and the corresponding traffic fatalities. States with higher levels of per capita alcohol consumption tended to exhibit lower average traffic fatalities, suggesting a potential inverse relationship between these two variables.

The negative correlation implies that, on average, States with higher alcohol consumption may experience a reduced incidence of traffic fatalities. While correlation does not imply causation, these findings prompt further inquiry into the nuanced factors influencing road safety. Possible explanations may involve variations in public transportation usage, law enforcement practices, or cultural attitudes towards alcohol.
