# Global-Layoffs-Analysis-EDA.sql
Overview

This project explores global layoffs data using SQL. The main objective is to clean, standardize, and analyze the data to uncover trends in workforce reductions across companies, industries, and countries over time.

Dataset

Source: -- https://www.kaggle.com/datasets/swaptr/layoffs-2022

Description: The dataset contains information about layoffs globally, including company names, industry, location, total laid-off employees, percentage of workforce affected, dates, funding stage, country, and funds raised.

Project Objective

Clean the raw data and create a reliable staging table.

Standardize fields such as company names, industries, countries, and dates.

Perform Exploratory Data Analysis (EDA) to identify trends and patterns.

Highlight top companies with the most layoffs and monthly/annual trends.

SQL Queries Used
Data Cleaning

Removed duplicates using ROW_NUMBER() and DENSE_RANK().

Trimmed whitespaces in company names.

Standardized industry and country names.

Converted date column from text to DATE format.

Handled NULL and empty values in key columns.

Exploratory Data Analysis (EDA)

Calculated rolling total of layoffs per month.

Ranked companies by total layoffs per year using window functions.

Identified top 5 companies with highest layoffs each year.

Insights

Standardized data enabled accurate aggregation and ranking.

Monthly and yearly trends revealed peaks in layoffs across industries.

Certain companies consistently appeared in top layoffs per year.

Rolling totals helped visualize overall workforce reduction trends.

Skills Demonstrated

SQL Data Cleaning & Transformation

Use of CTEs, Window Functions, and Aggregations

Exploratory Data Analysis (EDA)

Handling NULLs, duplicates, and inconsistent data
