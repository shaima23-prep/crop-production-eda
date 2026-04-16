 Agricultural Crop Production — Exploratory Data Analysis

## Overview
A complete exploratory data analysis (EDA) of global crop production data from the FAO (Food and Agriculture Organization of the United Nations), covering wheat, corn, and soybean production across 180+ countries from 2000 to 2023.

## What this project does
- Loads and inspects raw FAO production data
- Cleans and standardizes the dataset (missing values, data types, filtering)
- Generates 5 publication-quality charts
- Summarizes key findings with statistics

## Charts produced
| Chart | Description |
|-------|-------------|
| `01_global_trend.png` | Global production trends over time for all 3 crops |
| `02_top10_countries.png` | Top 10 countries by total production |
| `03_crop_comparison.png` | Total production comparison across the 3 crops |
| `04_heatmap.png` | Year-by-country production heatmap |
| `05_decade_comparison.png` | Average production by decade |

## Key findings
- Maize (corn) is the most produced crop globally by volume
- China and the United States consistently dominate production
- Global soybean production grew significantly after 2010
- The 2010s decade saw the highest average production across all crops

## How to run

### 1. Install dependencies
```bash
pip install pandas matplotlib seaborn
```

### 2. Get the data
1. Go to [FAOSTAT](https://www.fao.org/faostat/en/#data/QCL)
2. Select: Crops → All countries → Wheat, Maize, Soybeans → 2000–2023
3. Download as CSV
4. Save as `FAOSTAT_crops.csv` in the same folder as the script

### 3. Run the script
```bash
python crop_production_eda.py
```

Charts will be saved in the `charts/` folder.

## Tools used
- Python 3.x
- Pandas — data loading, cleaning, aggregation
- Matplotlib — chart creation
- Seaborn — statistical visualizations

## Dataset source
FAO — Food and Agriculture Organization of the United Nations  
[https://www.fao.org/faostat/en/#data/QCL](https://www.fao.org/faostat/en/#data/QCL)  
