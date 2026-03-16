# DV-ScreenSense
ScreenSense: Kids’ Screentime Visualization System
1. System Overview

ScreenSense is a data analytics and visualization platform designed to analyze and visualize children's screen time patterns across multiple demographic and behavioral dimensions.

The system analyzes data from the Indian Kids Screentime 2025 dataset and produces insights based on:

• Age groups
• Gender
• Urban vs Rural location
• Device types
• Activity categories
• Weekday vs Weekend usage

The platform provides interactive dashboards and visual analytics that help:

• Parents understand usage habits
• Educators evaluate learning vs entertainment screen exposure
• Policymakers identify behavioral trends across regions

The output is delivered through visual dashboards and analytical reports.

2. System Architecture

High-level architecture:

Dataset Source (Kaggle)
        ↓
Data Ingestion
        ↓
Data Cleaning & Feature Engineering
        ↓
Analytics Engine
        ↓
Visualization Engine
        ↓
Dashboard Layer
        ↓
Insight Reports


Logical architecture:

Raw Dataset
     ↓
Data Processing Layer (Pandas)
     ↓
Analytics Layer (Statistical + ML)
     ↓
Visualization Layer (Matplotlib / Seaborn / Plotly)
     ↓
Dashboard Layer (Power BI / Tableau)
     ↓
End Users (Parents / Educators / Policymakers)
3. Tech Stack
Data Handling
Python

Libraries:
• pandas
• numpy

Purpose:
Data cleaning, transformations, feature engineering.

Visualization
• matplotlib
• seaborn
• plotly

Used for:
• exploratory data analysis
• statistical visualization
• interactive plots.

Dashboard
• Tableau
or
• Power BI

Features:
• interactive filters
• drill-down analytics
• dynamic dashboards.

Documentation
• Jupyter Notebook
• GitHub repository
• PDF report
• Presentation slides

4. Dataset Description
   
Dataset Source:
Kaggle — Indian Kids Screentime 2025

Main dataset includes:
• demographic data
• device usage patterns
• activity categories
• daily screen hours.
