Agricultural Crop Production Analysis (FAOSTAT EDA)

Project Overview
This project performs an Exploratory Data Analysis (EDA) on global agricultural crop production data sourced from FAOSTAT.  
The goal is to understand long-term production trends for major crops and analyze how production has evolved over time across decades.

---

 Objectives
- Clean and preprocess FAOSTAT crop production data
- Analyze production trends over time
- Compare key crops (Wheat, Maize, Soya beans)
- Visualize global agricultural patterns
- Generate insights from real-world agricultural data

---

Dataset
- **Source:** FAOSTAT (Food and Agriculture Organization of the United Nations)
- **Content:** Crop production statistics by country, year, and crop type
- **Key variables:**
  - Country
  - Crop
  - Year
  - Element (Production / Area harvested)
  - Value (metric tons)

---

Tools & Libraries
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

 Data Processing Steps
- Removed missing values
- Standardized column names
- Filtered relevant crops:
  - Wheat
  - Maize (corn)
  - Soya beans
- Selected production-related data
- Aggregated data by year and crop
- Created decade-based analysis

---

Key Analyses Performed
- Global crop production trends over time
- Yearly production comparison between crops
- Decade-based production analysis
- Crop-wise distribution and growth patterns

---

 Visualizations
The project includes:
- Line chart: Global production trends (2000–2023)
- Comparative bar charts across decades
- Crop-wise production evolution over time

All charts are saved in the `charts/` folder.

---

Key Insights
- Maize shows strong and consistent production growth over time
- Wheat remains relatively stable compared to other crops
- Soya beans production shows significant growth in recent decades
- Global production patterns vary significantly by crop type and time period

