# Prediction model for Kickstarter projects

The idea behind this challenge is to **explore the dataset**, build a **prediction model** from it and then code a **Python module** that serves the model

## The dataset
Kickstarter is one of the main online crowdfunding platforms in the world. The dataset (you can download it on https://www.kaggle.com/kemical/kickstarter-projects) contains more de 300,000 projects launched on the platform in 2018, and contains the following columns:

- **ID**: internal ID, _numeric_
- **name**: name of the project, _string_
- **category**: project's category, _string_
- **main_category**: campaign's category, _string_
- **currency**: project's currency, _string_
- **deadline**: project's deadline date, _timestamp_
- **goal**: fundraising goal, _numeric_
- **launched**: project's start date, _timestamp_
- **pledged**: amount pledged by backers (project's currency), _numeric_
- **state**: project's current state, _string_; **this is what you have to predict**
- **backers**: amount of poeple that backed the project, _numeric_
- **country**: project's country, _string_
- **usd pledged**: amount pledged by backers converted to USD (conversion made by KS), _numeric_
- **usd_pledged_real**: amount pledged by backers converted to USD (conversion made by fixer.io api), _numeric_
- **usd_goal_real**: fundraising goal is USD, _numeric_

## Goal
The goal is to predict whether a project will be successful or not. 