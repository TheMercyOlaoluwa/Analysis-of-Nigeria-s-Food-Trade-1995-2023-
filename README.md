# Analysis of Nigeria's Food Trade (1995-2023)

This is an exploratory data analysis (EDA) of Nigeria's food import and export trends from 1995 to 2023. The project uses data from UNCTAD to analyse the monetary value of Nigeria's food trade.

## Project Goal

The objective is to understand the structure of Nigeria's food trade by answering three main questions:
1.  What is the overall trend of food imports vs. exports?
2.  What are the primary food categories driving imports and exports?
3.  What is the processing level (e.g., Raw, Processed) of these key products?

## Methodology

1.  **Data Sourcing & Cleaning:** Sourced eight separate CSVs from UNCTAD, each containing a different metric (e.g., Export Value, Import Value, YoY Growth, etc.).
2.  **Data Wrangling:** Merged the eight files into a single, clean DataFrame.
3.  **Feature Engineering:** Extracted `Process` and `FoodCategory` from a single messy column to enable detailed analysis.
4.  **Analysis:** Aggregated and visualized different metrics:
  * Overall Import/Export trends (value, % of total merchandise, YoY growth).
  * Trade broken down by major food category .
  *  Trade broken down by processing level .
  *  Deep dives into the top import (Cereals) and top export (Cocoa).

## Key Findings

The analysis reveals a significant structural imbalance in Nigeria's food trade:

* **Growing Trade Deficit:** Nigeria is a consistent and large net importer of food. Food imports regularly constitute 10-30% of the nation's total merchandise imports, while food exports are minimal (1-5%)
* **Imports = Raw Cereals:** Food imports are dominated by **Cereals** (totaling over $44.4B). 92.3% of these cereal imports are unprocessed **Raw** materials.
* **Exports = Processed Cocoa:** Food exports are overwhelmingly concentrated in one category: **Cocoa** (totaling over $15.1B). 86.1% of these exports are **Minimally Processed**.

  
