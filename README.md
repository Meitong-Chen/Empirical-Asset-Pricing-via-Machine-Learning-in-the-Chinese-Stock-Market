# Empirical Asset Pricing via Machine Learning in the Chinese Stock Market

This repository contains the data, scripts, and analysis for the research paper titled "Empirical Asset Pricing via Machine Learning in the Chinese Stock Market" authored by Yang Yuting and Chen Meitong. The project investigates the use of various machine learning models to predict risk premiums in the Chinese stock market using a dataset spanning from 2010 to 2022.

## Project Overview

The goal of this project is to apply multiple machine learning techniques to explore their effectiveness in empirical asset pricing within the context of the Chinese stock market. We compare models including Ordinary Least Squares (OLS), Elastic Net, Principal Component Regression (PCR), Partial Least Squares (PLS), Random Forests, Gradient Boosted Regression Trees, and Neural Networks.

## Dataset

The dataset consists of 30 firm characteristics collected from the Chinese stock market between 2010 and 2022. These characteristics include but are not limited to:
- Net asset value per share
- Price-to-book ratio
- Earnings per share change
- Annual turnover

## Models

- **Ordinary Least Squares (OLS)**
- **Elastic Net**
- **Principal Component Regression (PCR)**
- **Partial Least Squares (PLS)**
- **Random Forest**
- **Gradient Boosted Regression Trees (GBRT)**
- **Neural Networks**

Each model's directory contains:
- Python scripts for model training and evaluation
- Jupyter notebooks with data analysis and visualization

## Usage

To run the scripts, ensure you have Python installed, along with the necessary libraries mentioned in `requirements.txt`.

```bash
pip install -r requirements.txt
python script_name.py
