# Iphone-sales-data-analysis
# iPhone.csv Dataset

## Overview
The `iphone.csv` file contains data related to various models of iPhones. The dataset includes information such as model specifications, release dates, prices, and other relevant attributes. This dataset is useful for data analysis, product comparisons, trend analysis, and machine learning tasks related to iPhones.

## File Structure

The `iphone.csv` file consists of the following columns:

1. **Model**  
   The model name of the iPhone (e.g., "iPhone 13", "iPhone 12 Pro", etc.).

2. **Release Year**  
   The year the iPhone model was released (e.g., "2021", "2020").

3. **Storage Capacity (GB)**  
   The available storage options for the iPhone model in gigabytes (e.g., 64, 128, 256).

4. **Color**  
   The available colors for the iPhone model (e.g., "Black", "White", "Blue", etc.).

5. **Price (USD)**  
   The retail price of the iPhone model in USD.

6. **Screen Size (inches)**  
   The screen size of the iPhone model, measured diagonally in inches.

7. **Battery Life (hrs)**  
   The estimated battery life of the iPhone model in hours (e.g., 10 hours, 12 hours).

8. **Chipset**  
   The chipset used in the iPhone model (e.g., "A14 Bionic", "A15 Bionic").

9. **Camera (MP)**  
   The megapixel count of the iPhone's rear camera(s).

## Example Data

| Model           | Release Year | Storage Capacity (GB) | Color        | Price (USD) | Screen Size (inches) | Battery Life (hrs) | Chipset        | Camera (MP) |
|-----------------|--------------|------------------------|--------------|-------------|----------------------|---------------------|----------------|-------------|
| iPhone 13       | 2021         | 128                    | Red          | 799         | 6.1                  | 19                  | A15 Bionic     | 12          |
| iPhone 12 Pro   | 2020         | 256                    | Graphite     | 999         | 6.1                  | 17                  | A14 Bionic     | 12          |
| iPhone SE (2020)| 2020         | 64                     | White        | 399         | 4.7                  | 13                  | A13 Bionic     | 12          |

## Usage

This dataset can be used for various purposes, including:

- **Product comparison:** Compare different iPhone models based on features like price, storage, and battery life.
- **Trend analysis:** Analyze how iPhone specifications and prices have evolved over the years.
- **Predictive modeling:** Build models to predict iPhone prices or other attributes based on various features.
- **Data visualization:** Create visualizations to show trends or distributions of iPhone models, prices, or specifications.

## Prerequisites

To use this dataset for analysis or machine learning purposes, you may need the following:

- Python (preferably version 3.x)
- Pandas library (`pip install pandas`)
- Matplotlib/Seaborn for visualization (`pip install matplotlib seaborn`)
- Jupyter Notebook (optional for interactive analysis)

## Data Loading Example

```python
import pandas as pd

# Load the dataset
iphone_data = pd.read_csv('iphone.csv')

# Display the first few rows of the dataset
print(iphone_data.head())
