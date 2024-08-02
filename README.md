# Betting Predictive Model

Welcome to the Betting Predictive Model project repository. This project aims to analyze betting survey data to understand the behavior, 
demographics, and potential risks associated with betting activities. The analysis provides insights for a project that equips youths with the necessary tools 
and education to mitigate the risks of gambling addiction.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data Description](#data-description)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [How to Run the Project](#how-to-run-the-project)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Betting is a common activity with significant social and economic implications. Understanding the demographics and behaviors associated with betting can help design effective interventions. 
This project leverages survey data to analyze betting patterns, demographics, and other related factors.

## Project Structure

The repository contains the following main components:
- `data/`: Directory containing the survey data files.
- `notebooks/`: Jupyter notebooks for data analysis and visualization.
- `src/`: Source code for data processing and analysis.
- `results/`: Directory for storing analysis results and figures.
- `README.md`: Project overview and instructions.

## Data Description

The survey data includes the following columns:
- `Age`: Age of the respondent.
- `Gender`: Gender of the respondent.
- `Highest Level of Education`: Educational attainment of the respondent.
- `Betting`: Boolean indicating if the respondent bets (True/False).
- `Amount Spent`: Amount of money spent on daily betting.
- `Income`: Daily income of the respondent.

## Exploratory Data Analysis

The analysis includes:
- Descriptive statistics of the survey data.
- Demographic analysis (age, gender, education).
- Betting behavior analysis (frequency, amount spent).
- Correlation analysis between age, income, and betting behavior.
- Visualization of key findings using pie charts, bar graphs, histograms, and heatmaps.

## How to Run the Project

1. **Clone the repository:**
   ```sh
   git clone https://github.com/liciemw/Betting-predictive-model.git
   cd Betting-predictive-model
   
2. **Set up the virtual environment:**
   python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`

3. **Install dependencies:**
   pip install -r requirements.txt
   
4. **Run the Jupyter notebooks:**
   jupyter notebook notebooks/

5. **Run the analysis scripts:**
   python src/your_analysis_script.py

   **Dependencies**
The project requires the following Python packages:

pandas
numpy
matplotlib
seaborn
scipy
Install them using:
pip install pandas, numpy, matplotlib, seaborn, scipy

**Contact**
For any questions or inquiries, please contact:

Email: alice214w@gmail.com
GitHub: liciemw

