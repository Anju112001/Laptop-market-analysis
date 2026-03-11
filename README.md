Laptop Market Analysis
Project Overview

This project performs an Exploratory Data Analysis (EDA) on a laptop market dataset to identify how hardware specifications and brand characteristics influence laptop pricing. The analysis focuses on uncovering patterns in laptop configurations, pricing trends, and brand positioning in the market.

The dataset contains 1,200+ laptop records and multiple technical attributes, including manufacturer, processor, RAM, storage, GPU, operating system, screen size, weight, and price. 

LAPTOP MILESTONE 1 (1)

The objective is to transform raw laptop specification data into meaningful insights about market trends, pricing drivers, and product segmentation.

Objectives

Analyze laptop market distribution across brands

Identify key factors influencing laptop price

Explore relationships between RAM, storage, CPU, and price

Examine laptop type distribution (Notebook, Ultrabook, Gaming, etc.)

Understand how operating systems and hardware configurations impact pricing

Dataset Features

The dataset contains the following attributes:

Company

TypeName

Inches (Screen Size)

ScreenResolution

CPU

RAM

Memory

GPU

Operating System

Weight

Price

These variables allow analysis of hardware specifications, product segmentation, and pricing behavior across different laptop brands. 

LAPTOP MILESTONE 1 (1)

Data Preprocessing

Several preprocessing steps were performed before analysis:

Removed irrelevant columns (e.g., Unnamed:0)

Handled missing values using median imputation

Converted data types from object to numeric

Removed special characters and units (e.g., kg in weight)

Treated outliers in features such as screen size and weight

These steps ensured the dataset was clean, consistent, and suitable for analysis.

Exploratory Data Analysis

Multiple visualizations were created to explore market patterns:

Brand Market Share

Identified which laptop brands dominate the market and which brands position themselves in the premium price segment.

RAM vs Laptop Type

Analyzed RAM distribution across laptop categories such as:

Gaming

Notebook

Ultrabook

Workstation

RAM vs Price

Examined how increasing RAM impacts laptop pricing.

Storage vs Price

Compared different storage configurations (SSD, HDD, hybrid) and their effect on price.

Screen Size & Weight Distribution

Studied how screen size and laptop weight vary across devices.

Company vs Price

Analyzed average laptop price by brand to identify premium and budget manufacturers.

Key Insights

Lenovo, Dell, and HP dominate the market in terms of product volume.

Apple laptops have the highest average price, indicating premium market positioning.

Higher RAM configurations significantly increase laptop price, especially for gaming laptops.

Ultrabooks and workstations tend to be more expensive compared to standard notebooks.

Most laptops fall within the 13–15 inch screen size category, indicating a market standard.

Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook
