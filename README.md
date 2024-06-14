# Navigate and Clean Data using Python Pandas

In this repository, a sample data set is taken from Kaggle and cleaned using Python.

<a href="https://www.kaggle.com/" target="_blank">Visit Kaggle</a>

## Food Choices Dataset

This dataset includes information on food choices, nutrition, preferences, childhood favorites, and other related topics from college students. It contains 126 responses. Below is a minimally cleaned version of the dataset.

## Project Description

The primary objective of this project is to demonstrate data cleaning techniques using Python's Pandas library. The dataset used in this project is sourced from Kaggle and focuses on various food-related preferences of college students.

## Features

- **Data Navigation**: Load, explore, and analyze the dataset using Pandas.
- **Data Cleaning**: Perform basic data cleaning operations such as handling missing values, removing duplicates, and standardizing data formats.
- **Insights Extraction**: Generate insights and summaries from the cleaned data.

## Basic commands to tryout!
- import pandas as pd
- data = pd.read_csv('data/food_choices.csv')
- print(data.info())
- data = data.dropna()
- data = data.drop_duplicates()
- data.to_csv('cleaned_data/cleaned_food_choices.csv', index=False)
