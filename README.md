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

