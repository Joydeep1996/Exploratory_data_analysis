# Asheville Airbnb Exploratory Data Analysis

This repository contains a focused exploratory data analysis (EDA) of Airbnb listings and reviews for Asheville, North Carolina.

## Repository Structure
- `listing_nc_asheville.csv` – Listing-level data with location, property details, pricing, and host attributes.
- `review_nc_asheville.csv` – Review-level data containing timestamps, reviewer info, and a precomputed sentiment score.
- `Joydeep_Mishra_Data_Analysis.ipynb` – Jupyter notebook performing the analysis.
- `Joydeep_Mishra_Data_Analysis.pdf` – PDF export of the notebook for quick viewing.

## Key Analysis Steps
1. **Data loading and cleaning** using `pandas` and `numpy` to merge datasets, handle missing values, and create derived metrics such as `price_per_person`.
2. **Exploratory analysis** with `seaborn` and `matplotlib` to visualize distributions, correlations, and trends across time and geography.
3. **Regression modeling** with `statsmodels` to explore how factors like minimum nights, price, host traits, and amenities relate to review sentiment.

## Running the Notebook
1. Install dependencies: `pip install pandas numpy seaborn matplotlib statsmodels jupyter`.
2. Start Jupyter: `jupyter notebook`.
3. Open `Joydeep_Mishra_Data_Analysis.ipynb` and run cells sequentially.

## Next Steps
To extend this project, consider modularizing the analysis into scripts, adding tests for data processing functions, and exploring additional modeling approaches or data sources.

