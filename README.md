# Vancouver Urban Trees – EDA & Interactive Visualization

This project was developed as part of the **Data Visualization course** within the **UBC Key Capabilities in Data Science** certificate program. It focuses on analyzing a subset of the publicly available [Vancouver Street Trees dataset](https://opendata.vancouver.ca/explore/dataset/public-trees/information/) to uncover patterns in urban forestry through exploratory data analysis (EDA) and interactive Altair visualizations.

[![View on GitHub Pages](https://img.shields.io/badge/View-GitHub%20Pages-blue)]([https://yourusername.github.io/your-repo-name/](https://nadimkhn.github.io/van-trees/))

## Objective

To explore spatial, temporal, and species-related patterns in Vancouver's urban forest, and communicate insights via an interactive dashboard. The questions addressed include:

1. How has the total number of trees planted changed over the years?
2. What are the most common tree species in Vancouver?
3. How does tree diameter (as a proxy for age) vary across neighbourhoods?
4. How is species diversity distributed spatially across the city?

## Key Visualizations

The final report includes Altair-based interactive visualizations:

- **Line Chart** showing the number of trees planted over time.
- **Bar Charts** for top 10 most common species.
- **Box Plots** of tree diameter by neighbourhood.
- **Interactive Choropleth Map** with filters for species and diameter metrics.

All visualizations are embedded within an interactive Altair dashboard using compound and layered charts, dynamic selections, and filtering.

## Techniques and Methods

- **Data wrangling:** `pandas`
- **Visualization library:** `Altair`
- **Interactivity:** Altair’s `selection`, `condition`, `transform_filter`, and `facet` features
- **Spatial mapping:** Overlaid filtered tree data on a GeoJSON neighborhood map

## Sample Insights

- Tree planting saw a sharp increase post-2010, aligning with the city’s Greenest City Action Plan.
- The most common tree species are dominated by a few types (e.g., *Acer platanoides*, *Quercus robur*).
- Neighbourhoods like West End and Mount Pleasant show both mature and younger tree populations, suggesting diverse planting efforts.
- Certain communities have lower tree diameter averages, hinting at recent planting initiatives or urban development impacts.

## 🔧 Tech Stack

- Python 3.x
- Pandas
- Altair
- Jupyter Notebooks
