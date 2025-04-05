---

# 🚗 Car Price Prediction & EDA Dashboard (Power BI Project)

## 📌 Problem Statement

The automotive industry is dynamic and highly competitive. Car prices vary significantly depending on several factors such as engine specifications, fuel system, car body type, number of doors, aspiration, and performance metrics like horsepower. This project aims to explore how these features influence the pricing of cars and to visualize the insights in a clear and interactive way using Power BI. The ultimate goal is to help users and stakeholders understand key patterns behind pricing and support data-driven decision-making.

---

## 🎯 Project Objectives

- Clean and preprocess raw car price data using Excel
- Perform Exploratory Data Analysis (EDA) to understand feature relationships
- Compare price trends between gas and diesel cars
- Create KPI cards for key metrics like Avg Price, Max, Min, and Std Dev using DAX
- Build an interactive Power BI dashboard with dynamic visuals and slicers
- Derive insights into which car features most impact price
- Visualize trends such as horsepower vs. price using a line chart

---

## 🛠 Tools Used

| Tool      | Purpose                          |
|-----------|----------------------------------|
| Excel     | Data cleaning and preprocessing  |
| Power BI  | Dashboard creation & visualization |
| DAX       | KPI metrics and custom measures  |

---

## 📂 Project Structure

```
📁 CarPricePrediction-Dashboard/
├── 📄 README.md ← You are here
├── 📊 Car_Price_Predicrion_Analysis.pbix ← Power BI dashboard file
├── 📄 CarPrice_Assignment.csv ← Original dataset
├── 📄 CarPrice_Cleaned_Dataset.csv   ← Cleaned & preprocessed Excel file with FeatureStats sheet
├── 📸 CarPrice_Prediction_Analysis.png ← Dashboard image preview
```

---

## 📈 Dashboard Features

- ✅ **Slicers** for fuel type (gas/diesel)
- ✅ **KPI Cards** for:
  - Average Price
  - Min Price
  - Max Price
  - Price Standard Deviation
- ✅ **Bar Charts** showing average price by:
  - Cylinder number
  - Number of doors
  - Car body
  - Fuel system
- ✅ **Pie/Donut Charts** for aspiration and engine type
- ✅ **Line Chart** showing the trend between horsepower and price
- ✅ **Interactive Summary Table** for feature-level statistics

---

## 📊 Key DAX Measures Used

```DAX
Avg Price = AVERAGE(CarPrice_Cleaned_Datset[price])
Min Price = MIN(CarPrice_Cleaned_Datset[price])
Max Price = MAX(CarPrice_Cleaned_Datset[price])
Price Std Dev = STDEV.P(CarPrice_Cleaned_Datset[price])
```

---

## 🔍 Key Insights

- Cars with more cylinders tend to have a higher average price
- Diesel cars showed a slightly higher average price than gas cars
- Body type (e.g., hardtop, sedan) plays a significant role in pricing
- Turbo aspiration and certain fuel systems impact price noticeably
- Higher horsepower generally leads to higher pricing, confirmed via line chart

---

## 📷 Dashboard Preview

![image](https://github.com/user-attachments/assets/29b07362-873e-4138-a7d9-5cbac6e5bc5c)


---

## 📥 How to Use

1. Clone this repo or download the `.pbix` and `.csv` files
2. Open the Power BI file (`.pbix`) in **Power BI Desktop**
3. Review the visuals, slicers, and KPI cards
4. Use the `CarPrice_Cleaned_Dataset.csv` file to view how feature statistics were prepared in Excel

---

