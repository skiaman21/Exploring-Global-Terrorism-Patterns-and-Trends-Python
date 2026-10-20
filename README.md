# 🌍 Global Terrorism Analysis (2012–2022)

## 📌 Project Overview

This project explores global terrorism patterns and trends from 2012 to 2022 using Python. The main goal is to understand how terrorism incidents, fatalities, and injuries have changed over time and which countries have been most affected.

The project uses data analysis and visualization techniques to identify important patterns, compare countries, study yearly changes, and understand relationships between different variables.

## 🎯 Objectives

- Analyze the yearly trend of terrorism incidents.
- Identify the countries with the highest number of incidents.
- Compare terrorism incidents across countries and years.
- Analyze fatalities and identify the most affected countries.
- Find countries that frequently rank among the highest in incidents.
- Study the relationship between incidents, fatalities, and injuries using correlation analysis.

## 🛠️ Technologies Used

- **Python** – Data analysis and processing
- **Pandas** – Data cleaning, grouping, and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Writing and running the analysis

## 📂 Project Structure

```text
Global-Terrorism-Analysis/
│
├── Global_Terrorism_Analysis.ipynb
├── 1776311688-P5-Exploring Global Terrorism Patterns & Trends.xlsx
└── README.md
```

## 🔍 Analysis Performed

### 1. Data Exploration
- Viewed the first and last rows of the dataset.
- Checked column names, data types, and dataset information.
- Generated descriptive statistics.
- Checked missing values.

### 2. Yearly Incident Analysis
Grouped the data by year to calculate the total number of incidents and visualize changes over time.

### 3. Country-Wise Incident Analysis
Calculated total incidents for each country and identified the five countries with the highest totals.

### 4. Country Trends Over Time
Compared yearly incident counts across countries to identify increases and decreases during the analysis period.

### 5. Top 10 Countries by Year
Identified the ten countries with the highest incident counts for each year from 2012 to 2022.

### 6. Fatalities Analysis
Analyzed fatalities by year and country to identify years and locations with high numbers of deaths.

### 7. Country Ranking Analysis
Examined how frequently countries ranked first in incidents during the selected period.

### 8. Correlation Analysis
Used a correlation heatmap to study the relationships between incidents, fatalities, and injuries.

## 📊 Key Insights

- **Yearly trends:** The notebook's analysis identifies 2020 as the year with the highest incident count in the selected period.
- **Most affected countries:** Iraq recorded the highest total in the country-wise incident analysis, followed by Afghanistan.
- **Changes across countries:** Myanmar, Burkina Faso, and Mali showed increases in incidents in the analyzed period, according to the notebook's findings.
- **Fatalities over time:** The analysis identified 2015 as the year with the highest total fatalities among the years listed in the notebook's results.
- **Country rankings:** Iraq frequently ranked first in the yearly ranking analysis.
- **Correlation:** The correlation matrix showed a strong positive relationship between incidents and fatalities (0.86), incidents and injuries (0.86), and fatalities and injuries (0.91).



## 📈 Visualizations

The project includes visualizations such as:

- Line chart for yearly incidents
- Chart showing the top five countries by incidents
- Country-wise trend comparisons
- Subplots showing the top ten countries by year
- Fatalities analysis by year and country
- Correlation heatmap

These visualizations make it easier to understand patterns and compare results.

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/Global-Terrorism-Analysis.git
   ```

2. Open the project folder:

   ```bash
   cd Global-Terrorism-Analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl jupyter
   ```

4. Make sure the Excel dataset is available at the path used in the notebook. Update the file path if needed.

5. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `Global_Terrorism_Analysis.ipynb` and run the cells in order.

## 💡 Conclusion

This project demonstrates how Python can be used to analyze global terrorism data and discover patterns across years and countries. By combining data exploration, grouping, statistical analysis, and visualization, the project helps summarize changes in incidents and their human impact.

The project also provided practical experience in using Pandas for data manipulation, Matplotlib and Seaborn for visualization, and correlation analysis for understanding relationships between numerical variables.

## 👨‍💻 Author

**Aman Singh Rawat**

---

⭐ If you find this project useful, consider giving the repository a star.
