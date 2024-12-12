# 🌍 Emissions Data Dashboard

## 📋 Project Overview
This project focuses on developing an interactive dashboard for visualizing emissions data, including geographical mapping, analytics, and user-driven functionalities. The dashboard was built using **Python** with libraries such as **Pandas**, **Folium**, and **Dash** for data processing, visualization, and dashboard creation.

### Key Features
- **Map Visualizations**:
  - Emissions data plotted on maps, including heatmaps.
  - Ability to select a point on the map and plot custom squares to calculate emissions.
  - Multiline graphs for emissions comparison across different sites.
- **Data Insights**:
  - Average emissions over 932 km²: 1733 tons/km².
  - High-emission areas (9 km²) show up to 20x the average emissions.
  - 92% of black carbon emissions come from three specific sites.
- **User Interaction**:
  - Input coordinates to plot squares and calculate emissions.
  - Download plotted data for further analysis.
- **Accessibility**:
  - Dashboard is colorblind-inclusive.

## 🔧 Technologies Used
- **Python**: A high-level, fast, and flexible programming language.
- **Pandas**: For data cleaning and manipulation.
- **Folium**: For map visualizations.
- **Dash**: For creating the interactive dashboard.

## 📈 Data Transformation and Challenges
- Addressed missing values and zero emissions calculations.
- Standardized background emissions for consistent analysis.

## 🗺️ Maps and Visualizations
- Heatmaps to visualize emissions intensity.
- User-defined coordinate plotting for custom square-based analysis.
- Multiline graphs comparing emissions across sites.
- Pie charts for visual distribution analysis.

## 📊 Visualizations
Below are some sample visualizations included in the dashboard. Replace the placeholder text with titles and images for your actual visualizations.

### Interactive Map
<img src="https://github.com/user-attachments/assets/349d50d9-52f0-40dd-ab9f-548972316b82" alt="Alt Text" width="700" height="400">

### Heatmap Visualization
<img src="https://github.com/user-attachments/assets/57f28da7-961e-4791-a029-62a5a73faf8e" alt="Alt Text" width="700" height="500">



### Pie Chart Analysis
<img src="https://github.com/user-attachments/assets/9365c479-03ad-45b9-8852-e829e4ab616a" alt="Alt Text" width="500" height="570">

## 🧾 Findings
- For Carbon dioxide average emissions over an area of 932kmsq are 1733 tons/Km2. While average emissions in 3 high emissions areas are up to 20 times (for a square size of 9Kmsq) the normal average.
- For Carbon dioxide total emissions in an area of 932 Km2 are 1.6m tons. Yet, 54% of these emissions come from an area of 36.75 Km2.
-  Apart from Black Carbon, emissions of Carbon monoxide & Methane are low in the 3 areas. 92% of black carbon emissions are from the 3 sites.

## 🔮 Future Enhancements

- Currently, 3 sites are responsible for polluting most of the regions, further investigation is needed to find out the reasons behind this.
- Integrate high-resolution data for more granular analysis (zoom-in below 0.5 km).
- Replace plotted squares with circles centered at specific sites.
- Further investigate high-emission areas with refined data sources.

## 🤝 Contributions
Contributions and suggestions are welcome! Feel free to submit issues or pull requests.

## 📧 Contact
- **Author**: Raja Talha Tariq
- **Email**: [raja.talha.tariq@example.com](mailto:raja.talha.tariq@example.com)
