# 🌍Air Quality Index

A data analytics project that explores **global Air Quality Index (AQI) patterns** using pollutant data and geographical coordinates.  
The project uses **Python-based data analysis and visualization** techniques to understand pollution trends and relationships between pollutants.

## 📌 Project Overview

Air pollution is one of the most critical environmental challenges affecting human health and climate conditions worldwide.

This project analyzes **Air Quality Index (AQI)** data across multiple regions using statistical analysis and visualization techniques to uncover:

• Pollutant severity  
• Global pollution trends  
• Geographic pollution hotspots  
• Correlations between pollutants and AQI  

The goal is to transform raw environmental data into **meaningful insights for environmental monitoring and policy awareness.**

## 📊 Dataset Information

Dataset used:  
**AQI-and-Lat-Long-of-Countries.csv**

Features included:

| Column | Description |
|------|-------------|
| AQI Value | Overall Air Quality Index |
| CO AQI Value | Carbon Monoxide pollution level |
| Ozone AQI Value | Ozone pollution level |
| NO2 AQI Value | Nitrogen Dioxide pollution level |
| PM2.5 AQI Value | Fine particulate matter pollution |
| lat | Latitude of location |
| lng | Longitude of location |

Total records: **16,695**

## ⚙️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📈 Data Analysis & Visualizations

The project performs exploratory data analysis using multiple visualization techniques:

### 1️⃣ Average AQI by Pollutant
Identifies the pollutants contributing most to poor air quality.

### 2️⃣ AQI Distribution
Histogram showing how AQI values vary across locations.

### 3️⃣ Geographical AQI Mapping
Scatter plot visualizing AQI values using **latitude and longitude coordinates**.

### 4️⃣ Pollutant Variability
Box plots highlight distribution and outliers among pollutants.

### 5️⃣ Spatial Density Analysis
Hexbin plot reveals **pollution hotspots across global regions.**

### 6️⃣ Correlation Analysis
Heatmap showing relationships between pollutants and overall AQI.

## 🔍 Key Insights

• **PM2.5 shows the strongest impact on AQI levels**  
• Certain regions exhibit **high pollution clusters**  
• Pollutants show measurable correlations with overall AQI  
• AQI values vary significantly across different geographic areas
