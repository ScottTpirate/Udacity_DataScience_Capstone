# Udacity_DataScience_Capstone

### **Project Overview**

This data science project explores a comprehensive dataset from the Starbucks rewards mobile app, which simulates customer interactions with various promotional offers. These offers include advertisements, discounts, and buy-one-get-one-free (BOGO) promotions, each with specific conditions and validity periods that influence customer actions such as viewing or completing offers through purchases. The objective is to analyze how different demographic groups respond to these offers, with the ultimate goal of enhancing the effectiveness of Starbucks' marketing strategies to boost customer engagement and increase sales efficiency.

### **Problem Statement**

The primary challenge of this project is to synthesize transactional data, customer demographics, and promotional offer responses to identify which demographic groups are most responsive to different types of offers. By understanding these dynamics, Starbucks can better tailor its promotional efforts to maximize engagement and profitability, thereby improving customer satisfaction and optimizing marketing resource allocation.

### **Metrics**

To evaluate the effectiveness of promotional offers and the impact of predictive models on marketing strategies, the following metrics are utilized:
- **Correlation between Income and Total Spending**: This metric assesses the relationship between a customer's income and their spending behavior on the app, providing insights into how income levels might influence responsiveness to offers.
- **Distribution of Recommended Offers**: Analyzes how offers are allocated across customer segments based on spending behaviors and demographic characteristics. This helps in assessing the effectiveness of targeted marketing strategies.
- **Mean Scores by Offer Type**: Calculates the average response score for each type of offer to determine which offers are most appealing to customers, thereby guiding promotional focus.
- **Insights from Demographic Data**: Explores patterns and trends within the demographic data to identify which segments are most likely to engage with different types of offers.

These metrics are selected to directly measure the influence of promotional strategies on customer purchasing patterns and engagement, aligning closely with the project's goals.

### **Data Exploration**

The dataset is segmented into three main files, reflecting different aspects of customer interactions and promotional details:
- **portfolio.json**: Details the characteristics of each offer, such as type (e.g., BOGO, discount, informational), difficulty (minimum spend required to activate the offer), rewards, duration, and the channels through which the offers are distributed.
- **profile.json**: Provides demographic information about the app users, including age, gender, income, and membership start date, which are crucial for segmenting customers and tailoring offers.
- **transcript.json**: Contains logs of customer transactions and interactions with offers, detailing when offers are received, viewed, and completed, as well as purchase amounts and times.

Initial explorations reveal a wide range of engagement levels with offers, significant diversity in demographic attributes, and various patterns in purchasing behavior, which are essential for understanding how different customer segments interact with promotional strategies.

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
