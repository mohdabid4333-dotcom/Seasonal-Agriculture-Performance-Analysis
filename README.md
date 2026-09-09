# Seasonal Agriculture Performance Analysis

## Project Overview

Seasonal Agriculture Performance Analysis is a data analytics project focused on understanding agricultural performance across different crops and seasons.

The project analyzes agricultural data to identify patterns in crop yield, seasonal performance, profitability, resource usage, environmental factors, and overall agricultural efficiency.

The analysis uses Python-based data analytics and visualization techniques to transform agricultural data into meaningful, data-driven insights and recommendations.

---

## Objectives

- Analyze agricultural performance across different crops and seasons.
- Compare average crop yield across seasons.
- Identify the most profitable crops.
- Identify the best crop and season combination.
- Analyze relationships between agricultural factors and crop yield.
- Compare revenue, cost, and profit across crops.
- Evaluate crop profitability using profit margins.
- Identify potential outliers in key agricultural variables.
- Generate data-driven recommendations for agricultural decision-making.

---

## Dataset

The dataset contains **4,000 agricultural records** with information related to farm characteristics, environmental conditions, agricultural inputs, crop production, profitability, water usage, and disease/pest risk.

### Key Variables

- Farm Area (Hectares)
- Rainfall (mm)
- Average Temperature (°C)
- Humidity (%)
- Sunlight Hours per Day
- Soil pH
- Soil Moisture (%)
- Nitrogen (kg/ha)
- Phosphorus (kg/ha)
- Potassium (kg/ha)
- Fertilizer (kg/ha)
- Pesticide (Litre/ha)
- Seed Quality Score
- Yield (Tonnes/Ha)
- Production (Tonnes)
- Market Price (INR/Tonne)
- Total Cost (INR)
- Revenue (INR)
- Profit (INR)
- Water Used (m³)
- Water Efficiency (t per 1000m³)
- Disease/Pest Risk (%)

---

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab**
- **Jupyter Notebook**
- **GitHub**

---

## Analysis Performed

### 1. Data Exploration

The dataset was explored to understand its structure, variables, and agricultural records before performing further analysis.

### 2. Seasonal Analysis

Crop performance was compared across:

- Zaid
- Kharif
- Rabi

Average yield and profit were analyzed for each season.

### 3. Crop Performance Analysis

Different crops were compared based on their:

- Average yield
- Production
- Revenue
- Cost
- Profit
- Profit margin

### 4. Crop + Season Analysis

Crop and season combinations were analyzed to identify the combination with the strongest overall performance.

The analysis identified:

**Sugarcane + Kharif** as the best-performing Crop + Season combination based on the analyzed profitability and yield measures.

### 5. Environmental Factor Analysis

Relationships between selected agricultural factors and Sugarcane yield were examined using correlation analysis.

The analyzed factors included:

- Rainfall
- Temperature
- Soil Moisture
- Fertilizer
- Water Usage

### 6. Correlation Analysis

A correlation matrix and heatmap were created to examine relationships among agricultural, production, financial, and resource-related variables.

### 7. Profitability Analysis

Revenue, total cost, and profit were compared across crops.

Profit margin was also calculated to evaluate profitability efficiency.

### 8. Outlier Analysis

Box plots were used to identify potential outliers in key agricultural performance variables, including:

- Yield
- Production
- Revenue
- Total Cost
- Profit
- Water Used

---

## Key Findings

- **Sugarcane** was the most profitable crop in the analyzed dataset, with an average profit of **₹817,187.99** and the highest profit margin of **59.56%**.
- **Chilli** was the second most profitable crop, with an average profit of **₹750,878.34** and a profit margin of **58.81%**.
- **Sugarcane + Kharif** was identified as the best Crop + Season combination, with an average yield of **53.46 Tonnes/Ha** and an average profit of **₹1,000,790.81**.
- **Kharif** had the highest average yield among the analyzed seasons.
- Profitability varied significantly across crops, with Pulses, Maize, Rice, and Wheat showing negative average profits in the analysis.
- The selected agricultural factors showed weak linear relationships with Sugarcane yield:
  - Rainfall: **0.283**
  - Temperature: **0.093**
  - Soil Moisture: **0.171**
  - Fertilizer: **0.058**
  - Water Usage: **0.074**
- The correlation analysis indicates that these individual factors should not be interpreted as direct causes of Sugarcane yield.

---

## Results

### Seasonal Yield Graph
<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/f0f3170d-b8bd-4bd0-ab69-6e1364465ece" />

### Seasonal Profit Graph
<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/bd6e5f2d-448e-4ffe-a2bf-bd6fd27cf59c" />

### Revenue vs Cost vs Profit by Crop Graph
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/66d99524-a08b-4e7a-b4fa-97faacdc9b1c" />

### Profit Margin by Crop Graph
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/e7232fc0-2f9b-4850-810a-d8ae34e70aa8" />

### Correlation Heatmap
<img width="1658" height="1390" alt="image" src="https://github.com/user-attachments/assets/1ba7d364-7186-4164-bfca-ff80bcd9faad" />

---

## Data-Driven Recommendations

Based on the analysis:

1. **Prioritize high-profit crops**  
   Sugarcane and Chilli can be considered strong options based on their high average profits and profit margins.

2. **Consider seasonal performance**  
   Kharif showed strong overall performance and should receive attention when planning crop-season combinations.

3. **Evaluate multiple factors together**  
   Agricultural decisions should consider yield, revenue, cost, profit, and resource efficiency rather than relying on a single factor.

4. **Optimize resource usage**  
   Water and fertilizer usage should be evaluated as part of a broader agricultural management strategy.

5. **Use data-driven crop planning**  
   Historical agricultural data can support better crop and seasonal planning and help identify potentially profitable combinations.

---

## Project Workflow

```text
Data Collection
      ↓
Data Exploration
      ↓
Data Analysis & Cleaning
      ↓
Seasonal Analysis
      ↓
Crop Performance Analysis
      ↓
Crop + Season Analysis
      ↓
Correlation Analysis
      ↓
Profitability Analysis
      ↓
Outlier Analysis
      ↓
Key Findings
      ↓
Data-Driven Recommendations
