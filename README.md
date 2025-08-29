# Indian Election Analysis (2009–2014)

A Jupyter Notebook–based exploration and visualization of Indian general election results from 2009 to 2014. This project aims to uncover voting trends, party performance, regional patterns, voter turnout, and demographic influences across different states and national levels.

## Table of Contents

- [Introduction](#introduction)  
- [Dataset Overview](#dataset-overview)  
- [Analysis Workflow](#analysis-workflow)  
- [Usage Instructions](#usage-instructions)  
- [Directory Structure](#directory-structure)  
- [Dependencies](#dependencies)  


## Introduction

This repository contains an interactive Jupyter Notebook (`Indian_Election_Data_Analysis.ipynb`) along with accompanying data for analyzing the Indian general election results of 2009 and 2014. The project’s primary goals are:

- Compare party performances across election years.  
- Analyze voter turnout trends both nationally and regionally.  
- Highlight key demographic and state‑level influences.  
- Leverage visualizations to illustrate insights clearly.

## Dataset Overview

The dataset included in this repository (`indian-national-level-election.csv`) contains aggregated election results at the national and state levels for both 2009 and 2014. Expected columns may include (but are not limited to):

- **Year** (2009 or 2014)  
- **State/Union Territory**  
- **Total Votes Cast**  
- **Voter Turnout (%)**  
- **Party-wise Vote Share / Seats Won**  

*(Adjust column names as per the actual dataset.)*


## Analysis Workflow

1. **Data Loading & Cleaning:** Load the CSV, handle missing values, and ensure correct data types.  
2. **Exploratory Data Analysis (EDA):** Generate summary statistics, and visualize distributions of turnout and party performance.  
3. **Comparative Analysis:** Contrast metrics like turnout and vote share between 2009 and 2014, both overall and by state.  
4. **Visualization:** Use charts—bar plots, line graphs, maps (if included), etc.—to illustrate temporal and geographic trends.  
5. **Interpretation:** Annotate and discuss findings directly within the notebook narrative.

## Usage Instructions

To run the notebook locally:

```bash
git clone https://github.com/Ayush-Shah96/Indian-Election-Analysis-2009-14.git
cd Indian-Election-Analysis-2009-14
python3 -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
pip install -r requirements.txt  # or `pip install pandas matplotlib seaborn` if no file
jupyter notebook Indian_Election_Data_Analysis.ipynb

exit
```

## Directory Structure

Indian-Election-Analysis-2009-14/
├── Indian_Election_Data_Analysis.ipynb     # Main analytical notebook
├── indian-national-level-election.csv      # Election data file
├── requirements.txt                        # Python dependencies (optional)
└── LICENSE                                 # MIT License

## Dependencies

Key Python libraries likely needed:
- pandas — for data manipulation
- matplotlib / seaborn — for visualization
- jupyter — to run the notebook
