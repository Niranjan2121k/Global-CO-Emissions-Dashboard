# Analyzing Global CO2 Emissions with Tableau

## ✨ **Project Overview**
This data visualization project offers an in-depth exploration of global CO2 emissions using Tableau. Leveraging historical and contemporary data, the project delivers interactive dashboards that visualize the evolution of emissions, uncover population-to-emission correlations, and highlight geographical disparities. The aim is to foster better understanding of climate dynamics and support informed policy-making.

---

## 🔎 **Objective**
- Visualize the historical share of CO2 emissions across different regions from 1740 to 2020.
- Analyze how CO2 emissions in 2021 relate to population sizes of countries.
- Highlight country-wise disparities in per capita CO2 emissions.
- Present a visual storytelling dashboard that is intuitive and data-rich.

---

## ⚖️ **Tools & Techniques Used**
- **Tool:** Tableau (2024 version) for all visualizations.
- **Skills Applied:**
  - Time series and trend visualization
  - Interactive map creation and customization
  - Scatter plots and correlation analysis
  - Dashboard layout and storytelling design

---

## 📈 **Detailed Data Insights**

### 1. **CO2 Emissions Global Share by Year (1740–2020)**

This line chart displays the **percentage share of global CO₂ emissions** contributed by different countries or regions over time, from **1740 to 2020**.

<img width="1530" alt="Screenshot 2025-04-15 at 2 41 02 PM" src="https://github.com/user-attachments/assets/f2ed8a89-859f-4801-8c89-0ab9da3d0c8f" />

---

## 📊 Chart Breakdown

### **X-Axis (Horizontal):**  
- **Label:** Year  
- **Range:** 1740 to 2020  
- Shows the timeline of global industrial activity and emissions.

### **Y-Axis (Vertical):**  
- **Label:** % of Total CO₂  
- **Range:** 0% to 100%  
- Indicates the share each region contributes to global CO₂ emissions.

---

## 🔍 Key Observations

- **Pre-1800s:**  
  One country or region contributes nearly all emissions (~100%), likely reflecting the early industrial revolution in a single region.

- **1800s to early 1900s:**  
  - Gradual decline of the dominant region.
  - Emergence of new contributors as global industrialization expands.

- **Mid-1900s (WWI & WWII Era):**  
  - Peaks and valleys in certain countries' emissions.
  - Countries like the US and USSR likely show noticeable growth during these periods.

- **Post-1950s:**  
  - Global distribution of emissions increases.
  - More countries industrialize and contribute to emissions.

- **2000–2020:**  
  - Emerging economies rise in share.
  - Some developed countries reduce their global share due to policy changes or outsourcing.

---

## 🎨 Color Encoding

- **Color Gradient (Blue → Purple → Orange → Yellow):**  
  Represents **CO₂ per capita**.  
  - **Cool colors (blue/purple):** Low CO₂ per person  
  - **Warm colors (orange/yellow):** High CO₂ per person

---

## 🛠 Interactive Features

- **Top N Filter :**  
  Allows selection of the top N countries or regions based on CO₂ per capita.
---

## 🧠 Insights Gained

- Visualizes how **global CO₂ responsibility has shifted** across centuries.
- Highlights periods of rapid industrial growth and decline.
- Helps compare **total vs. per capita emissions** for a nuanced view.
- Useful for understanding **historical and regional impacts** of emissions.
- From 1740 to early 1900s, CO2 emissions were heavily dominated by Western countries such as the UK and USA.
- Post-1950, there's a noticeable rise in emissions from Asian countries, particularly China and India.
- The chart reveals how economic growth, industrial revolutions, and globalization have re-distributed emission sources globally.
- The color gradient indicates the per capita emissions, adding a deeper layer of insight on emissions intensity.

---

### 2. 🌐 **CO2 Emissions by Country (Map View)**

This **choropleth world map** visualizes the **CO₂ emissions per capita** for each country, using a diverging color scale to highlight the variation in emissions intensity across the globe.

<img width="1528" alt="Screenshot 2025-04-15 at 2 44 43 PM" src="https://github.com/user-attachments/assets/a416690b-b30e-41e3-a58f-77d100497620" />

---

## 🌍 Map Overview

### **Color Legend:**
- Located on the right, the color scale represents **CO₂ emissions per capita**.
- **Dark Blue → Yellow → Red Gradient:**
  - **Dark Blue:** Low CO₂ per capita (e.g. many African and South Asian countries)
  - **Purple:** Moderate emissions (e.g. parts of Europe, South America)
  - **Orange/Red:** High CO₂ per capita (e.g. North America, Australia, parts of the Middle East)

---

## 🗺 Key Insights

- **North America (U.S. & Canada):**  
  Bright red and orange, indicating **very high CO₂ emissions per person**.

- **Europe & Russia:**  
  Varies from pink to red, indicating moderate to high per capita emissions.

- **Middle East (e.g., Saudi Arabia, UAE):**  
  Extremely high per capita emissions (yellow to bright red).

- **Africa & South Asia:**  
  Mostly deep blue and purple shades, reflecting **very low CO₂ emissions per capita**.

- **China & India:**  
  Purple to orange tones, showing **growing but still moderate per capita emissions**.

- **Australia:**  
  High per capita emissions, shown in orange-red.

---

## 📌 Notes

- This visualization does **not represent total emissions**, but rather **per person** emissions.  
  For example, although China emits more CO₂ in total, its **per capita emission is lower** than that of countries like the US or Saudi Arabia.

- Useful for understanding **emission inequality**, where **developed nations have far higher per-person contributions** to global emissions.

---

> 🧭 Great for climate impact studies, policy comparison, and educational insights on environmental responsibility across nations.
- **Visualization Type:** Filled map (choropleth).

## 🧠 Insights Gained
- The map highlights North America, China, Russia, and parts of the Middle East as major contributors to CO2 emissions.
- Countries in Africa and South America show comparatively lower emissions.
- The map's color gradient (from blue to red) reveals high per capita emissions in developed and oil-rich nations.
- Geographic disparities underline different development trajectories and energy usage patterns.

---

### 3. **CO2 Emissions (2021) vs. Population by Country**

This bubble scatter plot compares **total CO₂ emissions** against **population** for various countries in **2021**. It provides a multi-dimensional view using color, size, and position.

<img width="1528" alt="Screenshot 2025-04-15 at 2 46 14 PM" src="https://github.com/user-attachments/assets/1c00b27b-0665-4871-9b1c-88a21a881741" />

---

## 🔍 Chart Breakdown

### **Axes**
- **X-axis:** Total CO₂ emissions (in thousands of metric tons)
- **Y-axis:** Population (in millions)

### **Color Gradient **
- Represents **CO₂ emissions per capita**
- Scale:  
  - **Purple/Blue** → Low per capita emissions  
  - **Red/Orange** → High per capita emissions

### **Bubble Size **
- Indicates the **temperature change** attributed to each country
- Larger circles = Greater climate impact through temperature increase

### **Diagonal Reference Line**
- Serves as a **reference benchmark**
- Countries on the line emit CO₂ proportionally to their population  
- **Above the line**: Lower per capita emissions  
- **Below the line**: Higher per capita emissions

---

## 🌐 Insights

- **China & India (Top-Left Quadrant):**  
  Extremely high population but relatively lower per capita emissions (small bubbles, cooler colors).  
  China still has high total emissions due to scale.

- **United States (Far-Right):**  
  Significantly high total emissions with a smaller population compared to China → **very high per capita CO₂** (larger, red bubble below the line).

- **Other Developed Nations (Lower-Right):**  
  Countries like Canada and Australia appear farther right with smaller populations, indicating **excessively high per capita emissions**.

- **Low-Emission Countries (Bottom-Left Cluster):**  
  Most nations cluster here with low emissions and smaller populations.

---

## 📌 Conclusion

This chart clearly shows:
- **Emission inequality**, where some nations contribute disproportionately more per person.
- The importance of factoring in both **population size** and **per capita contribution** in climate accountability.
- China and India dominate in terms of total emissions due to large populations.
- The USA, despite a lower population, shows significantly higher per capita emissions.
- Gulf countries such as Qatar and UAE, although small in population, exhibit very high per capita emissions.
- The visualization clearly distinguishes countries with sustainable practices from high-emission anomalies.

---

## 🚧 **Challenges Faced**
- Cleaning and structuring datasets from various sources to align with Tableau's visualization needs.
- Handling missing values and normalizing per capita data to avoid skewed insights.
- Ensuring geographic consistency for country codes in map visualizations.
- Balancing visual appeal with analytical clarity in dashboard design.

---

## 🌍 **Key Outcomes**
- Produced **three impactful Charts** that provide different lenses into CO2 emissions data.
- **Discovered anomalies** like high per capita emissions in small countries and declining emissions in formerly industrial giants.
- Built an interactive **visual narrative** that stakeholders and policy advocates can explore.
- Improved data visualization and storytelling proficiency in Tableau.

---

## 📄 **Next Steps**
- Integrate economic and energy consumption data for richer analysis.
- Track emissions targets vs. actual performance by region.
- Add predictive modeling using Tableau's forecasting tools.

---
# Final Dashboard

<img width="1404" alt="Screenshot 2025-04-15 at 2 47 55 PM" src="https://github.com/user-attachments/assets/74577785-b7f7-4531-8c9f-4459e6cb77c8" />

