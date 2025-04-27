# App Genre Analysis for App Store and Google Play

## Project Overview
This project analyzes mobile app data from the App Store and Google Play to find the most common and potentially successful app genres. 

Our goal is to identify app profiles that are popular on both platforms, which helps in deciding new app development directions with lower risk and higher user engagement.

## Validation Strategy
Our validation strategy for launching new apps includes:
1. Build a minimal Android version and launch it on Google Play.
2. If the app performs well, develop it further.
3. If the app remains profitable after 6 months, build and release an iOS version for the App Store.

## Project Structure
- Load App Store and Google Play datasets.
- Clean and inspect the datasets.
- Build reusable functions to:
  - Create frequency tables showing genre percentages.
  - Display genre percentages in descending order.
- Analyze the most common app genres on each platform.

## Files
- `test.ipynb`: The main Jupyter Notebook containing data exploration and analysis.

## Functions
- `freq_table_percentages(df, column_name)`: Returns a frequency table with percentages for a selected column.
- `display_freq_table(df, column_name)`: Displays the frequency table sorted in descending order.

## How to Use
1. Open the `Profitable_app.ipynb` file.
2. Run all the cells to:
   - Load and inspect the datasets.
   - Generate and view frequency tables for App Store (`prime_genre`) and Google Play (`Category` and `Genres`).

## Technologies Used
- Python
- Pandas
- Jupyter Notebook


