Big Mart Sales Data Analysis

Project Overview

This project analyzes the Big Mart sales dataset using Python and machine learning techniques. The goal is to preprocess the data, handle missing values, and train predictive models to estimate sales.

Dataset

The dataset used is Train.csv, containing sales-related attributes such as:

Item_Identifier

Item_Weight

Item_Fat_Content

Item_Visibility

Item_Type

Item_MRP

Outlet_Identifier

Outlet_Establishment_Year

Outlet_Size

Outlet_Location_Type

Outlet_Type

Item_Outlet_Sales

Libraries Used

pandas

numpy

matplotlib

seaborn

sklearn

xgboost

Data Preprocessing

Handled missing values in Item_Weight using forward fill.

Filled missing Outlet_Size values based on Outlet_Type and Outlet_Location_Type.

Encoded categorical variables using LabelEncoder.

Exploratory Data Analysis (EDA)

Distribution plots for Item_Weight and Item_Visibility using Seaborn.

Summary statistics using df.describe().

Machine Learning Models

XGBoost Regressor: Advanced model for improved accuracy.

Results

Successfully handled missing values.

Visualized data distributions.

