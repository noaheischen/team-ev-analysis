# Electric Vehicles and Their Environmental Effect

## In this project we will be analyzing electric vehicle populations within varying areas and try to identify a correlation between environmental health and electrical vehicle presence

In this project we will use online datasets that provide us information about different states and electric vehicle populations within them. By looking at this data alongside pollution and air quality datasets, we aim to find a possible correlation between electric vehicles and a more healthy environment. By describing this correlation we hope to further incentivize the purchase of electric ehicles and the prioritization of a healthy environment through the technologies we use daily. 

## Team Members

- Brandon Werba
- Noah Eischen
- Om Patel
- Noah Cha-Price
- Thomas Isaac


## Data Description

Describe the dataset(s) used in your project, including:

- EV data and Air Quality data taken from Kaggle datasets
- Data collected from the period 2018-2025.
- Data organized by state, visualizations created representing state, party affiliation, and air quality.


### Key Variables

| Variable Name | Description | Data Type | Units/Format | Notes |
| :-- | :-- | :-- | :-- | :-- |
| [variable 1] | [description] | [type] | [units] | [any special considerations] |
| [variable 2] | [description] | [type] | [units] | [any special considerations] |

## Methodology

Outline the approach taken to analyze the data, including:

- Exploratory data analysis techniques
- Statistical methods applied
- Machine learning models used (if applicable)
- Evaluation metrics


## Key Findings

Summarize the main discoveries and insights from your analysis. Include:

- Important patterns or trends identified
- Unexpected results
- Answers to the initial research questions
- Visualizations of key findings (reference to files in the repository)

## Installation and Setup

Instructions for setting up the project environment:

```bash
# Example installation commands
pip install -r requirements.txt
```
**note:** A requriements.txt is often used to list all the packages (e.g., pandas, numpy, scikit-learn) that are needed to run the project. You can create this file by running `pip freeze > requirements.txt` in your terminal.

## Project Structure

Explain the organization of files and directories in your repository:

```
├── data/               # Raw and processed data files
├── notebooks/          # Jupyter notebooks
├── src/                # Source code
├── results/            # Output files and visualizations
├── requirements.txt    # Required packages
└── README.md           # This file
```
**Note:** To get the above project structure (without needing to format it all manually), look up the [tree command](https://www.geeksforgeeks.org/tree-command-unixlinux/). You can use `tree` in the terminal in any directory to recursively list folders/files. I would suggest using `tree -L 1` (as shown above) to limit the depth of the tree to 1 level, as project codebases can get quite complex.

## Usage

Provide instructions on how to run your code and reproduce your results:

```python
# Example code snippet
from src.model import train_model
from src.visualization import visualize_results
model = train_model(data_path='data/processed/training_data.csv')
output = model.predict(new_data)
visualize_results(output)
```


## Future Work

Outline potential next steps or improvements for the project:

- Additional analyses that could be performed
- Features that could be added
- Ways to improve the current models or methods

## Acknowledgments

Credit data sources, tools, or individuals who contributed to the project.
