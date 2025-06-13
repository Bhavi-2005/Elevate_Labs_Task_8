# Elevate_Labs_Task_8
# 📊 Task 8: Simple Sales Dashboard Design (Tableau)

## 🎯 Objective
To create a clean, interactive Tableau dashboard that visualizes sales performance by category, region, and month using the Superstore dataset.

---

## 📁 Dataset Used
- **sample_-_superstore.csv**: Raw dataset containing order date, region, category, sales, and profit.
- **Superstore_Sales_Cleaned.csv**: Cleaned and processed version of the dataset, with added fields like `Month-Year` and removed nulls.

---

## 🧹 Data Cleaning
The data was cleaned using Python (Pandas) and saved as a cleaned CSV. Cleaning steps included:
- Removing null/missing rows
- Converting `Order Date` to datetime
- Creating a `Month-Year` field
- Ensuring numeric formatting for `Sales` and `Profit`

🔗 See the notebook:  
📓 **Task_8_Dataset_Cleaning_and_Processing.ipynb**

---

## 📊 Dashboard Features
The dashboard was created in **Tableau Public** and includes:

- 📈 **Line Chart**: Monthly Sales Trend (`Month-Year` vs. `Sales`)
- 📊 **Bar Chart**: Sales by Region (`Region` vs. `Sales`)
- 🍩 **Pie Chart**: Sales by Category (`Category` vs. `Sales`)
- 🎛️ **Slicers/Filters**: Interactive filters for Region and Category

---

## 🔗 Dashboard Link
🔍 View the interactive dashboard here:  
👉 [Click to Open in Tableau Public](https://public.tableau.com/app/profile/bhavishya.priyadarshini.v/viz/Task_8_Sales_Dashboard/Dashboard2?publish=yes)

---

## 📎 Files Included
| File Name                                  | Description                                 |
|-------------------------------------------|---------------------------------------------|
| `sample_-_superstore.csv`                 | Original dataset                            |
| `Superstore_Sales_Cleaned.csv`           | Cleaned dataset used in Tableau             |
| `Task_8_Dataset_Cleaning_and_Processing.ipynb` | Jupyter Notebook used for cleaning data |
| `Task_8_Sales_Dashboard.twb`             | Tableau workbook file                        |
| `Task_8_screenshort.PNG`                 | Dashboard screenshot                         |
| `Task_8_Key_Insights.txt`                | Key Insights of the dashboard                |
---

## 🔍 Key Insights
- East region had the highest total sales, followed closely by West.
- Furniture and Technology categories performed equally well.
- Office Supplies had the lowest contribution to sales.
- Sales spiked sharply early in the year, then remained relatively flat.
- Filters allow focused exploration by category and region.

📄 Full insights: [Task_8_Key_Insights.txt](./Task_8_Key_Insights.txt)

---

## 🛠 Tools Used
- Python (Pandas) for data cleaning
- Tableau Public for dashboard design

---

## 🧠 Learnings
- Data preprocessing significantly improves dashboard clarity.
- Tableau's slicers and marks allow intuitive business analysis.
- Visual storytelling helps uncover regional and product trends easily.

---


