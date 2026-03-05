Automobile Sales Analysis During Recession

This project explores the impact of economic recessions on automobile sales through a comprehensive set of data visualizations. Using Python and popular data science libraries, we analyze trends in sales, advertising expenditure, vehicle types, GDP, consumer confidence, and unemployment rates.

## 📊 Dataset

The dataset is fetched directly from an online source and contains **2,112 rows** and **15 columns**. Key features include:

- `Date`, `Year`, `Month`
- `Recession` (1 = recession period, 0 = non‑recession)
- `Consumer_Confidence`
- `Seasonality_Weight`
- `Price`
- `Advertising_Expenditure`
- `Competition`
- `GDP`, `Growth_Rate`
- `unemployment_rate`
- `Automobile_Sales`
- `Vehicle_Type` (e.g., SuperMiniCar, SmallFamilyCar, etc.)
- `City`

## 🛠️ Tools & Libraries

The analysis is performed using the following Python libraries:

- **pandas** – data manipulation and aggregation
- **numpy** – numerical operations
- **matplotlib** – basic plotting and customizations
- **seaborn** – advanced statistical visualizations
- **folium** – map plotting (imported but not used in final tasks)

## 📈 Visualizations & Tasks

### Task 1.1 – Line Chart: Yearly Automobile Sales
- Plots average automobile sales per year.
- Annotates two recession periods (e.g., 2008–2009, 2020).

### Task 1.2 – Advertising vs. Sales during Non‑Recession
- Dual‑line plot comparing average sales and advertising expenditure over non‑recession years.
- Highlights correlation (or lack thereof) between marketing spend and sales.


### Task 1.3 – Vehicle‑Wise Sales: Recession vs. Non‑Recession
- Grouped bar chart using seaborn.
- Shows how each vehicle type’s average sales differ between economic periods.

### Task 1.4 – GDP Variation: Recession vs. Non‑Recession
- Two side‑by‑side line charts (subplots) using `add_subplot()`.
- Compares GDP trends during recession and non‑recession years.

### Task 1.5 – Bubble Plot: Seasonality Impact on Sales
- Scatter plot of monthly sales with point size representing `Seasonality_Weight`.
- Focuses on non‑recession years to isolate seasonal patterns.

### Task 1.6 – Scatter Plots: Consumer Confidence & Price vs. Sales
- First scatter: consumer confidence vs. sales during recessions.
- Second scatter: vehicle price vs. sales during recessions.

### Task 1.7 – Pie Chart: Advertising Expenditure by Period
- Compares total ad spend during recession vs. non‑recession.

### Task 1.8 – Pie Chart: Ad Spend by Vehicle Type (Recession Only)
- Displays the proportion of advertising expenditure allocated to each vehicle type during recessions.

### Task 1.9 – Line Plot: Unemployment Rate vs. Sales per Vehicle Type
- Multi‑line plot showing how unemployment rate affects sales of different vehicle categories during recession.

## ▶️ How to Run

1. **Clone the repository** (if applicable) or download the notebook.
2. **Install the required libraries** (preferably in a virtual environment):

   ```bash
   pip install pandas numpy matplotlib seaborn folium

# Author
## Deepak Kumar Tamta
