# Excel & Data Analysis Roadmap


## Excel

### 1. Functions
- `UPPER`, `LOWER`, `PROPER`, `TRIM`
- `LEFT`, `MID`, `RIGHT`
- `CONCATENATE` and `&` (Ampersand)
- `ROUNDUP`, `ROUNDDOWN`
- `VLOOKUP`, `HLOOKUP`, `LOOKUP`, `XLOOKUP`
- `IF`, `IFS`, Nested `IF`, `IF` and `AND`, `SUMIF`
- Handling Excel Errors (`#DIV/0!`, `#N/A`, etc.)

### 2. Data Analysis
- `TEXTTOCOLUMNS`
- `=TEXT(cell, format)`
- `=MONTH(cell)`, `=DAY(cell)`, `=TEXT(cell, "dddd")`
- Wildcards: `?` replaces one character

### Keyboard Shortcuts
- Format currency: `Ctrl + Shift + $`
- Format two decimal places: `Ctrl + Shift + !`

### Data Gathering
- Random Data Generator: [Mockaroo](https://mockaroo.com/)
- Excel formula: `=RANDARRAY()`

---

## Pivot Tables
- Pivoting Data
- Changing Calculation Mode
- Filters / Slicers / Report Filters
- Grouping / Bucketing
- Value Settings
- Trends / Pivot Charts

📺 [YouTube Pivot Table Tutorial (36 pages)](https://www.youtube.com/watch?v=zuSNd1ZMfBI)

---

## Excel Dashboard Portfolio Project

### 1. Dashboard Page & Theme
- Font: Aptos Extra Bold
- Color: Slipstream
- TODO: Add images to Excel cells

### 2. KPIs Using Pivot Tables
- Use Data Model option when creating pivots

### 3. Creating a Data Model
- Tables: `Calls`, `Customers`
- Relationship via `CustomerID`
- Go to: PivotTable Analyze → Relationships → Create New Relationship

### 4. Power Pivot & DAX
- Add Measure:
  - Table Name: `calls`
  - Measure Name: `Call Count`
  - Formula: `=COUNTROWS(calls)`

---

## Data Analysis Project Tasks

1. Clean inconsistent shipping addresses
2. Assign data types to each column
3. Calculate total transaction value per user
4. Uniform date format (`YYYY-MM-DD`)
5. Count unique product categories
6. Group and count users by age range (e.g., 30–39)
7. Transaction frequency per user
8. Average transaction value per user
9. Analyze peak transaction times
10. Transactions by shipping address
11. Total units purchased per user
12. Handle missing values
13. Revenue by product category
14. Identify transaction peaks and drops
15. Identify and treat outliers
16. Time series trends from transactions
17. Segment users by value & frequency
18. Effective data visualizations
19. Actionable business insights
20. Best format for export (CSV, XLSX, etc.)

---

## Useful Resources

### ✅ TODO List
1. [Excel Exercises - Lessons](https://excelexercises.com/lessons.html)
2. Pivot Table 36-page notes + [Scribd exercises]
3. Hack The Box
4. Stats Course: [YouTube Playlist](https://www.youtube.com/playlist?list=PLqzoL9-eJTNAB5st3mtP_bmXafGSH1Dtz)
5. Power BI: [GeeksforGeeks Tutorial](https://www.geeksforgeeks.org/power-bi-tutorial/)

---

## Data Analyst Industry Certification Courses

1. [Google Analytics 4 Certification (GA4)](https://skillshop.docebosaas.com/learn/courses/14810/google-analytics-certification)
2. [Microsoft Learning Path (Data Analyst)](https://learn.microsoft.com/en-us/training/browse/?roles=data-analyst)
3. [DataCamp – Data Analyst with Python](https://www.datacamp.com/tracks/data-analyst-with-python)
4. [Tableau Certified Data Analyst ($250)](https://www.tableau.com/learn/certification/certified-data-analyst)
5. [Harvard edX – Data Science Certificate](https://pll.harvard.edu/series/professional-certificate-data-science)
6. [Power BI Analyst Certification – DataCamp](https://www.datacamp.com/certification/data-analyst-in-power-bi)
7. [Azure Fundamentals – DataCamp](https://www.datacamp.com/certification/azure-fundamentals)

---

> *Keep updating this roadmap as you complete tutorials and add new learnings.*
