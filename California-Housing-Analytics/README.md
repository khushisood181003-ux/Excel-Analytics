# California Housing Analytics Dashboard

## Project Overview

This project presents an interactive **California Housing Analytics Dashboard** developed in Microsoft Excel to analyze housing values, income levels, property characteristics, population, households, and ocean proximity.

The dashboard combines **Excel formulas, PivotTables, PivotCharts, slicers, calculated categories, and statistical analysis** to transform raw housing data into meaningful business insights.

---

## Project Objective

The objective of this project is to identify the major factors associated with California housing values and provide an interactive dashboard for exploring housing patterns across different income levels, property ages, and geographic locations.

The analysis focuses on:

* Understanding average and median house values
* Comparing housing values across ocean-proximity categories
* Examining the relationship between income and house value
* Comparing house values across income categories
* Analyzing house values by property age
* Identifying high-value housing segments

---

## Dataset

The project uses the **California Housing Dataset**, containing **20,640 housing records**.

### Dataset Variables

| Category                 | Variables                                             |
| ------------------------ | ----------------------------------------------------- |
| Geographic               | `longitude`, `latitude`                               |
| Property Characteristics | `housing_median_age`, `total_rooms`, `total_bedrooms` |
| Demographics             | `population`, `households`                            |
| Economic                 | `median_income`, `median_house_value`                 |
| Location                 | `ocean_proximity`                                     |
| Derived Variables        | `Income_Category`, `House_Age_Category`               |

Two additional analytical categories were created in Excel:

* **Income_Category**
* **House_Age_Category**

These categories were used to support comparative analysis through PivotTables and charts.

---

## Key Performance Indicators

| KPI                  |       Value |
| -------------------- | ----------: |
| Average House Value  | ₹206,855.82 |
| Average Income       |        3.87 |
| Total Population     |  29,421,840 |
| Total Households     |  10,310,499 |
| Average House Age    | 28.64 years |
| Average Rooms        |    2,635.76 |
| Average Bedrooms     |      536.84 |
| Total Housing Blocks |      20,640 |

---

## Dashboard Analysis

The dashboard contains interactive analysis using:

* PivotTables
* PivotCharts
* Slicers
* Excel formulas
* Calculated categories
* Scatter plot
* Trendline
* R² analysis

The major analytical dimensions are:

### 1. Ocean Proximity Analysis

Housing values vary considerably by proximity to the ocean.

**Key Insight:** Island properties have the highest average house value at approximately **₹3.80 lakh**, while inland properties have the lowest at approximately **₹1.25 lakh**.

### 2. Income Category Analysis

Housing values show a strong difference across income categories.

**Key Insight:** High-income areas have the highest average house value at approximately **₹3.78 lakh**, compared with **₹2.19 lakh** for medium-income areas and **₹1.34 lakh** for low-income areas.

### 3. House Age Analysis

Housing values were compared across old, moderate-age, and newer properties.

**Key Insight:** Older properties have the highest average house value at approximately **₹2.16 lakh**, compared with **₹2.02 lakh** for moderate-age properties and **₹1.92 lakh** for newer properties.

### 4. Income × Ocean Proximity Analysis

Income level and location were analyzed together to identify high-value housing segments.

**Key Insight:** Housing values are generally higher in high-income areas across locations, with **high-income properties near the ocean recording the highest average value at approximately ₹4.30 lakh**.

### 5. Median Income vs. House Value

A scatter plot with a trendline was used to examine the relationship between median income and median house value.

**Key Insight:** Median income shows a **moderate positive relationship** with median house value, with an **R² value of 0.4734**.

This indicates that median income explains approximately **47.34% of the variation** in median house value within the analyzed dataset.

---

## Business Insights

* **Island properties command the highest average house values**, while inland properties show the lowest average values.
* **Income is an important differentiating factor**, with high-income areas having substantially higher average house values.
* **Location also influences housing value**, with high-income properties near the ocean representing the highest-value segment.
* **Older properties show the highest average market value** among the defined house-age categories.
* **Median income has a moderate positive relationship with house value**, supported by an R² of 0.4734.

---

## Tools & Techniques

**Tool:**

* Microsoft Excel

**Techniques:**

* Excel Tables
* Excel Formulas
* Data Categorization
* PivotTables
* PivotCharts
* Slicers
* Scatter Plot
* Trendline
* R² Analysis
* Dashboard Design
* Exploratory Data Analysis

---

## Dashboard Features

The dashboard provides an interactive view of:

* Average house value
* Average income
* Population
* Households
* Average house age
* Average rooms
* Average bedrooms
* Total housing blocks
* Ocean proximity comparison
* Income category comparison
* House age comparison
* Income × ocean proximity analysis
* Income vs. house value relationship

Slicers allow users to interactively filter the PivotTable-based dashboard analysis.

---

## Key Takeaway

The analysis demonstrates that **income level and geographic location are important factors associated with California housing values**.

High-income areas, particularly those near the ocean, show the highest average house values. The positive relationship between median income and house value further supports the role of income in explaining housing-market variation.

---

## Project Skills Demonstrated

* Data Analysis
* Microsoft Excel
* Business Intelligence
* Dashboard Development
* Data Visualization
* PivotTable Analysis
* Exploratory Data Analysis
* Statistical Interpretation
* Insight Generation

---

## Project Files

* `California_Housing_Analytics_Dashboard.xlsx` — Interactive Excel dashboard
* `Dashboard.png` — Dashboard preview

---

## ⭐ Project Outcome

This project demonstrates the ability to transform a raw housing dataset into an **interactive, insight-driven Excel dashboard** and communicate analytical findings in a business-friendly format.
