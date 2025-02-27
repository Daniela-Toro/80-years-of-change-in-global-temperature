# 🌍 Is the Planet Heating Up? 80 Years of Global Temperature Change 🌡️🔥

## About the Datasets 📊
For this analysis, two datasets from Kaggle were used to segment the data by regions and subregions, allowing for a more detailed analysis of global temperature change. 🌎📈

### 📊 Dataset 1: Average Surface Temperature (1940-2024) 🌡️
📌 **Source:** [Kaggle - `average-monthly-surface-temperature.csv`](https://www.kaggle.com/datasets/samithsachidanandan/average-monthly-surface-temperature-1940-2024)

#### Description:
This dataset contains records of the average monthly surface temperature from 1940 to 2024. Global warming, primarily caused by greenhouse gas emissions, can lead to drastic changes in:
- ✅ Sea levels 🌊
- ✅ Ice cap and glacier balance 🏔️
- ✅ Precipitation patterns and extreme temperatures 🌧️🌞
- ✅ Impacts on health, agriculture, and biodiversity 🧑‍🌾🐾

#### Data Details:
- **Values represent the air temperature measured 2 meters above the ground.**
- Covers land, marine, and continental water surfaces.
- **Frequency:** Data recorded on the 15th day of each month.

#### 🔍 Key Attributes:

| Attribute                      | Description                                           |
|---------------------------------|-------------------------------------------------------|
| **Country Name**                | Name of the country                                   |
| **Country Code**                | ISO code of the country                               |
| **Year**                        | Year of the record                                    |
| **Day**                         | Day of the record                                     |
| **Average Surface Temperature** | Daily average surface temperature                     |
| **Average Surface Temperature.1** | Monthly average surface temperature                    |

---

### 🌎 Dataset 2: Mapping Countries by Continent and Region 🗺️
📌 **Source:** [Kaggle - `continents2.csv`](https://www.kaggle.com/datasets/andradaolteanu/country-mapping-iso-continent-region)

#### Description:
This dataset serves as a reference map to associate each country with its respective continent and subregion, facilitating analysis in Plotly and other visualization tools. 🌍🔍

#### 🔍 Key Attributes:

| Attribute                      | Description                                           |
|---------------------------------|-------------------------------------------------------|
| **Name**                        | Country name in English                               |
| **alpha-2**                     | 2-letter ISO code                                     |
| **alpha-3**                     | 3-letter ISO code                                     |
| **Country Code**                | Unique country code                                   |
| **Region**                      | Continent the country belongs to                      |
| **Sub-region**                  | Subcontinent of origin                                |
| **Intermediate Region**         | Intermediate region (if applicable)                   |
| **Codes for Region/Subregion/Intermediate Region** | Geographic classification codes         |

---

## Project Overview 🌍🔎
This project aims to analyze the global temperature trends over the last 80 years, examining how temperature has changed over time and the impact of various environmental and human factors on the climate. By combining the temperature data with country and region mappings, we can explore how different regions of the world have experienced temperature changes differently. 🌡️🌍

## Visualizations 📊💻
Throughout the project, several interactive visualizations have been generated to better understand the trends and patterns in the data:

- **Heatmaps 🌡️🔥**: Visual representations of temperature data across different regions, showing the variation in temperature over time.
- **Treemaps 🌳📊**: Interactive treemaps have been used to display the hierarchical relationships between countries, regions, and temperature changes.
- **Interactive Charts 📉**: Various interactive charts have been created to display trends over time, with the ability to explore specific years and regions.
- **Tooltips 💬**: Tooltips have been added to visualizations to provide additional insights when hovering over data points, offering a more detailed view of the data.
- **Maps 🗺️**: Geographical maps have been used to represent the temperature changes by region, allowing users to see how different parts of the world have been affected by global warming.

These interactive elements are designed to make the exploration of the data more engaging and insightful. 🎨💡

## Key Insights 💡
- **Global Warming Trends 🔥🌡️:** The data highlights significant increases in global temperatures, especially after 1980, with noticeable regional differences.
- **Temperature Anomalies 🌡️❗:** Extreme temperature events are becoming more frequent, and the data reveals patterns that suggest a direct correlation with human activities such as industrialization and deforestation.
- **Regional Variations 🌍:** Some regions, particularly the Northern Hemisphere, have seen a more significant increase in temperatures compared to other areas.

## Contributing 🤝
We welcome contributions to this project! If you'd like to contribute:
1. Fork the repository 🍴
2. Create a new branch 🌱
3. Submit a pull request 🔄

#### Install the required dependencies: pip install -r requirements.txt
