# 🎬 Movie Success Analysis – Final Project

This repository contains an exploratory data analysis and machine learning classification project using a movie dataset. The goal is to understand what factors influence a movie's success and to build a predictive model to classify movies as *Success* or *Flop* based on features such as budget, promotion, genre, and review sentiment.

## 📁 Files

- `Movie_Success_Analysis.ipynb` — Jupyter Notebook with data cleaning, analysis, and modeling.
- `CMSC320FinalProjectData.csv` — Dataset used in this project (*not included in repo – please add manually*).

## 📊 Features

- Cleaned and preprocessed raw movie data (handling outliers, duplicates, missing values)
- Performed sentiment analysis on reviews using **TextBlob**
- Conducted hypothesis testing (e.g., Chi-squared test)
- Visualized data using **Seaborn** and **Matplotlib**
- Built a Random Forest classifier with **Scikit-learn**
- Evaluated model using confusion matrix and accuracy score

## 💡 Highlights

- Found **Reviewer 1** to be the most important factor in movie success.
- Developed a classifier that uses both numerical and sentiment-based features to predict movie success.
- Cleaned significant errors within the large dataset such as outliers and duplicates

## 🛠️ Requirements

Install dependencies with:

```bash
pip install pandas scipy textblob seaborn scikit-learn matplotlib
