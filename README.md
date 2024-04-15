# Formula 1 Race Win Prediction Project

## Executive Overview

### 1. The Problem Area
In the fast-paced world of Formula 1, where split-second decisions define the outcome of races, our project harnesses the power of data science to not just interpret the past, but to predict the future. We delve into extensive datasets encompassing years of race history, driver and team dynamics, and track conditions, leveraging a blend of machine learning techniques to forecast who will win future races with enhanced precision. Readers will embark on a data-driven journey from raw numbers to predictive insights, uncovering the hidden patterns that influence the podium's composition. Our goal is to enhance prediction accuracy of race winners, thereby improving team strategies, betting odds, and fan engagement through data-driven insights.

### 2. The User
The beneficiaries of this project could include:

- Formula 1 Teams and Strategists: Refining race strategies and optimizing performance.
- Sports Analysts and Betting Companies: Gaining enhanced accuracy in race outcome predictions.
- The F1 Fan Base: Engaging more deeply with the sport through insights into race predictions and the influencing factors.
This initiative aims to foster a more informed and engaged Formula 1 community, integrating data-driven decisions and enhancing fan interactions within the sport's ecosystem. 

### 3. The Big Idea
Employing machine learning techniques, this project aims to surpass traditional prediction methods by identifying patterns and insights within extensive datasets. Utilizing regression analysis, decision trees, and gradient boosting techniques, we strive to enhance the precision of predictions.

### 4. The Impact
The aspiration of this project is to test out various data science modelling methods to see if we can predict the likely race winner of each race. The project successfully leveraged large datasets, including historical race outcomes, driver and team performance, and race day conditions, to build a robust predictive model. Key insights revealed that the most influential factors for predicting F1 race winners were qualifying positions, cumulative points (at stage of season), how long a driver had been in F1 and with their team, and which team they drove for. The model demonstrated notable accuracy in forecasting race winners, making it a valuable tool for teams, bettors, and fans seeking strategic insights.

The analysis also highlighted the financial viability of the model using 2024 F1 data, suggesting that it could effectively aid betting strategies and potentially generate profit in the betting industry. Personal learnings emphasized the importance of systematic data analysis and model evaluation in achieving reliable predictions. Looking ahead, the project intends to simplify the model for reduced computational demands and enhance its predictive capabilities by forecasting influential pre-race variables. Further automation of the data collection process and integration with AWS to improve user experience are also planned to refine the model's applicability and accessibility in the dynamic Formula 1 environment.

You can find the conclusions to the project in the Conclusions notebook "9. F1_Conclusions_and_Next_Steps.ipynb"

### 5. The Data
Utilizing data from official F1 website (formula1.com, OpenF1 API, and Ergast F1 APIs, this project aims to create a comprehensive predictive model. The datasets include race results for each driver, grid positions, driver, car and team characteristics, dynamic race elements, and more, offering a holistic view of Formula 1 racing dynamics. The dataset ranges from 1995-2023.

## Project Structure

Below is the file structure of the project, outlining where specific parts of the project are located and their purpose:

```plaintext
project-root/
│
├── .github/                # GitHub-specific metadata and configuration
├── Charts/                 # Visualizations and charts generated from the data
├── Conda_Environment/      # The Conda environment files necessary for reproducing the analysis environment.
├── Modelling/              # Model development scripts, including tuning and validation
├── Notebooks/              # Jupyter notebooks for exploratory data analysis and prototyping. NB the notebooks are in number order
├── Presentations/          # Presentation materials and slides
├── .gitignore              # Specifies untracked files to ignore
├── README.md               # Overview and documentation for the project
└── requirements.txt        # List of dependencies to replicate the analysis environment

## Notebooks

1. `F1_data_collection.ipynb`: Collecting data from various F1 APIs.
2. `F1_eda_starter.ipynb`: Initial exploratory data analysis of the F1 datasets.
3. `F1_question_driven_EDA.ipynb`: Further analysis driven by specific research questions.
4. `F1_preprocessing.ipynb`: Data preprocessing steps to prepare for modeling.
5. `F1_Models.ipynb`: Initial machine learning models and their performance.
6. `F1_Feature_Engineering.ipynb`: Feature engineering techniques to improve model performance.
7. `F1_Models_v2.ipynb`: Second iteration of model building with enhanced features.
8. `F1_Model_interpretability.ipynb`: Interpretation of the models and feature importances.
9. `F1_Conclusions_and_Next_Steps.ipynb`: Summary of findings and future work.

### Prerequisites
- Git: [Installation guide](https://git-scm.com/downloads)
- Conda: [Installation guide](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)


## Getting Started

To run this project, clone the repo and install the required Python packages. NB - the Conda environment I used, is in the "Conda_Environment" folder:
 
### Acknowledgments (WIP)
The original idea came from this article by Veronica Nigro: https://towardsdatascience.com/formula-1-race-predictor-5d4bfae887da. I want to thank her for the inspiration for my project and for giving me a north star to aim for.
