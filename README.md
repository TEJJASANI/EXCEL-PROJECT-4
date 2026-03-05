# Smart Farming Yield 2024 Dataset 🚜📊

## 🌾 Overview
**Smart Farming Yield 2024** tracks **500 farms** across 5 crops and 5 regions. Complete 2024 season data with yield outcomes, environmental factors, and farming practices.

**Total Yield**: 2,016,463 kg  
**Average Yield**: 4,033 kg/hectare  
**Coverage**: Jan-Dec 2024, 501 complete records

## 📈 Key Statistics

### Top Performing Crops
| Crop    | Farms | Avg Yield | Total Yield  |
|---------|-------|-----------|--------------|
| Soybean | 108   | **4,257** | 459,736 kg   |
| Wheat   | 92    | 4,078     | 375,138 kg   |
| Maize   | 111   | 3,983     | 442,063 kg   |

### Regional Leaders
| Region      | Avg Yield | Total Yield |
|-------------|-----------|-------------|
| **South India** | **4,123** | 375,183 kg |
| East Africa | 4,053     | 433,691 kg |

## 🛠️ Data Fields (24 Columns)
```
farm_id, region, crop_type, soil_moisture_%, soil_pH
temperature_C, rainfall_mm, humidity_%, sunlight_hours
irrigation_type, fertilizer_type, pesticide_usage_ml
sowing_date, harvest_date, total_days, **yield_kg_per_hectare**
Yield_Category, sensor_id, NDVI_index, crop_disease_status
NDVI_Health, Yield_Efficiency
```

## 📁 File Structure
```
Smart-Farming-Yield-2024/
├── DASHBOARD__Smart_Farming_Yield_2024.xlsx
│   ├── Smart_Farming_Yield_2024 (500 rows × 24 cols)
│   ├── Summary sheets (Sheet7-9)
└── README.md
```

## 💡 Key Insights
- **Soybean** yields 5.6% above average → Scale production
- **NDVI > 0.7** = +15% higher yields  
- **Inorganic fertilizer** = 4,087 kg/ha (vs Organic 4,039)
- **51% farms** achieved High Yield status
- **South India** = highest regional average despite fewer farms

## 📊 Analysis Ready
- Clean sensor data (no missing values)
- Categorized yields (High/Medium/Low)
- Pre-computed efficiency scores
- Ready for ML models, dashboards, research

<img width="1519" height="946" alt="image" src="https://github.com/user-attachments/assets/c55c2406-4024-4354-a5c8-d58550ff5165" />

