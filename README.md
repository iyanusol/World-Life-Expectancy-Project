
# World Life Expectancy – Power BI Dashboard

This project explores global **life expectancy**, **adult mortality**, and **infant deaths** to understand how health, education, and economic indicators shape outcomes across countries.

It is based on **Project 1 – World Life Expectancy** from Alex The Analyst’s Power BI course, with additional design, layout, and storytelling refinements.

---

![Dashboard Page 1](https://github.com/iyanusol/World-Life-Expectancy-Project/blob/main/images/Dashboard%20Page%201.png)

## 📊 Project Overview

The dashboard answers key questions such as:

- What is the **average global life expectancy** in this dataset?
- How do **adult mortality** and **infant deaths** vary across countries and over time?
- How do health indicators like **HIV prevalence, BMI, measles, and polio vaccinations** relate to life expectancy?
- What is the relationship between **schooling (education)**, **GDP**, and health outcomes?
- Where are the biggest **regional disparities** and opportunities for improvement?

The report is fully interactive with slicers for **Country** and **Year**.

---
![Dashboard Page 2](https://github.com/iyanusol/World-Life-Expectancy-Project/blob/main/images/Dashboard%20Page%202.png)

## 🧮 Dataset

- **Name:** World Life Expectancy dataset  
- **Source:** Provided as part of Alex The Analyst’s Power BI course  
- **Grain:** Country–Year level  
- **Key fields:**  
  - `Country`, `Year`, `Status` (Developed/Developing)  
  - `Life_expectancy`, `Adult_mortality`, `Infant_deaths`  
  - `HIV_AIDS`, `Measles`, `Polio`, `BMI`  
  - `Schooling`, `GDP`, `Population`, and other health indicators  

> Note: Raw data is not included here if restricted by the course license.  
> You can obtain the dataset directly from the course materials or from the recommended public source.

---
![Dashboard Page 3](https://github.com/iyanusol/World-Life-Expectancy-Project/blob/main/images/Dashboard%20Page%203.png)

## 🛠 Tools & Skills Demonstrated

- **Power BI Desktop**
- **Power Query** for:
  - Data type conversions
  - Handling missing values
  - Removing duplicates and outliers
- **Data Modeling**
  - Star-style model with cleaned fact table
  - Relationships between country, time, and indicator fields
- **DAX Measures**
  - Average Life Expectancy
  - Total Adult Mortality
  - Total Infant Deaths
- **Report Design & UX**
  - Custom theme and consistent colour palette
  - Card KPIs, scatter plots, clustered columns, line charts, and maps
  - Bookmarks, navigation buttons, and page-level tooltips
  - Narrative insight text to support non-technical stakeholders

---
![SQL Cleaned data](https://github.com/iyanusol/World-Life-Expectancy-Project/blob/main/images/Cleaned%20Data.png)

## 📄 Dashboard Pages

### Page 1 – Global Overview

**Goal:** Give a high-level snapshot of global life expectancy and mortality.

Key elements:

- **KPI Cards** for:
  - Total Adult Mortality (~483K)
  - Total Infant Deaths (~89K)
  - Average Life Expectancy (~69 years)
- **Donut Chart:** Adult Mortality vs Life Expectancy range
- **BMI vs Adult Mortality (Scatter):**
  - Shows how BMI relates to adult mortality across countries
- **Status & Schooling vs GDP (Scatter):**
  - Compares **Developed vs Developing** countries
  - Highlights that countries with higher schooling-years tend to have higher GDP
- **Narrative Text:** Summarises global life expectancy patterns and the need for stronger health systems.

---

### Page 2 – Health Indicators & Regional Patterns

**Goal:** Explore how specific health indicators interact with life expectancy.

Key elements:

- **BMI vs Adult Mortality Insight Panel:**
  - Explains the two main clusters in the scatter plot  
  - Suggests that undernutrition and poor healthcare access are major drivers of mortality
- **Health Indicators vs Life Expectancy (Combo Chart):**
  - Infant deaths, HIV/AIDS, and BMI shown against life expectancy over time
  - Helps reveal whether health investments are paying off
- **Map – Life Expectancy by Country:**
  - Bubble map showing which countries have higher or lower life expectancy
- **Regional Disparities Text Panel:**
  - Highlights ongoing gaps between developed and developing regions
  - Emphasises opportunities for vaccination, maternal health, and education improvements

---
![Data Cleaning](https://github.com/iyanusol/World-Life-Expectancy-Project/blob/main/images/Project%201%20Data%20Cleaning-2.png)

### Page 3 – Education, Economy & Infant Mortality

**Goal:** Connect education and economic growth to child health outcomes.

Key elements:

- **Education & Economic Growth Insight Panel:**
  - Describes the positive relationship between years of schooling and GDP
- **Infant Deaths by Year (Column + Line):**
  - Shows long-term trends in infant mortality
  - Indicates gradual improvement over the years
- **Infant Deaths by Status (Bar):**
  - Compares **Developing vs Developed** countries  
  - Makes clear that infant deaths are dramatically higher in developing regions
- **Infant Death by Country (Map):**
  - Highlights geographic clusters where infant mortality remains high
  - Helps identify regions that may need targeted health interventions

---

## 🔍 Key Insights

- The **global average life expectancy** in this dataset is around **69 years**, but there is large variation between countries.
- **Adult and infant mortality** are significantly higher in developing countries, especially where healthcare access is limited.
- Higher **HIV prevalence** and lower **vaccination rates** are associated with lower life expectancy.
- Countries with **higher schooling levels** tend to have **higher GDP** and **better health outcomes**.
- **Infant deaths** generally decline over time, but some regions still lag behind, showing the need for sustained investment in health and education.

---
![Custom Adobe Visuals](https://github.com/iyanusol/World-Life-Expectancy-Project/blob/main/images/Custom%20visuals%20with%20Adobe%20(1).png)

## 🚀 How to Use This Report

1. Download the `.pbix` file:
   - `World_Life_Expectancy.pbix`
2. Open it in **Power BI Desktop**.
3. Use the slicers at the top of the report:
   - Filter by **Country** or **Year**
4. Navigate between pages using the **home icon** and page tabs.
5. Hover over visuals for tooltips and additional context.

---
![Dashboard Page 1](https://github.com/iyanusol/World-Life-Expectancy-Project/blob/main/images/Dashboard%20Page%201.png)

## 📁 Repository Structure

```text
World-Life-Expectancy/
│
├── World_Life_Expectancy.pbix
├── README.md
├── images/
│   ├── page1-overview.png
│   ├── page2-health-indicators.png
│   └── page3-infant-mortality.png
└── data/              # optional
    └── world_life_expectancy.csv
