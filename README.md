# Udacity_DataScience_Capstone

### Section 1: Project Definition

#### Project Overview

This project involves analyzing customer behavior on the Starbucks rewards mobile app using simulated data that mimics real user interactions. The goal is to understand how different demographic groups respond to various offers sent through the app. Offers range from advertisements to discounts and buy-one-get-one-free promotions. Each offer has a validity period and requires different user actions, such as viewing or completing the offer by making qualifying purchases.

#### Problem Statement

The primary challenge is to combine transaction, demographic, and offer data to determine which demographic groups respond best to which type of offer. This will enable Starbucks to optimize its marketing strategies and increase the effectiveness of its promotional campaigns, leading to increased customer satisfaction and sales.

#### Metrics

The metrics for evaluating the effectiveness of different offers include:
- **Conversion Rate**: The percentage of offers viewed that lead to a completed transaction within the offer’s validity period.
- **Lift**: The increase in purchasing behavior attributable to the offer compared to normal purchasing patterns.
- **Return on Investment (ROI)**: Calculated as the net profit from the redeemed offers divided by the cost of issuing the offers.

These metrics are chosen because they directly measure the impact of offers on customer purchasing behavior, which is central to the project’s objectives.

### Section 2: Analysis

#### Data Exploration

The data is structured into three main files:
- **portfolio.json**: Contains details about the offers, including type (BOGO, discount, informational), difficulty (minimum spend required), reward, duration, and channels.
- **profile.json**: Includes demographic information about the users such as age, gender, income, and the date they became a member.
- **transcript.json**: Records transactions and interactions with offers, including when offers are received, viewed, and completed.

Preliminary analysis shows varied distributions in demographics, and transaction data shows a range of user engagement levels with the offers.

---

### Files
- **portfolio.json:** Contains details about the offers sent during the test period, including offer type, duration, and difficulty level.
- **profile.json:** Demographic data for each customer, such as age, gender, and income.
- **transcript.json:** Event log of customers' interactions with the offers, including receiving, viewing, and completing an offer, as well as transaction details.
- **Starbucks_Capstone_notebook.ipynb:** Jupyter notebook containing all the code and analysis.

### Dependencies
To run the code in this project, you will need Python 3.x along with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- sklearn

You can install these packages via pip:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

### Installation
Clone this repository to your local machine to get started with the project:
```bash
git clone https://github.com/your-username/starbucks-capstone-project.git
cd starbucks-capstone-project
```

### Usage
To run the analysis, navigate to the cloned directory and start the Jupyter Notebook:
```bash
jupyter notebook Starbucks_Capstone_notebook.ipynb
```

Follow the cells in the notebook which guide you through the data loading, preprocessing, analysis, and modeling stages.

### How It Works
- **Data Loading:** The notebook starts by loading the three JSON files into pandas DataFrames.
- **Data Cleaning and Preprocessing:** The data is cleaned by handling missing values and encoding categorical variables.
- **Exploratory Data Analysis (EDA):** Data is visualized using histograms, bar charts, and scatter plots to understand customer demographics and behavior.
- **Modeling:** Implements a Funk SVD algorithm to predict user responses to different offers and a Random Forest classifier to predict customer behavior.
- **Evaluation:** The models are evaluated using metrics like MSE and accuracy, and findings are tested statistically using ANOVA.

### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


---
