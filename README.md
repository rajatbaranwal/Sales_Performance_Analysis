# 📊 Sales Performance Analysis (Level 4 Project)

### 🧠 Overview
This project analyzes company sales data to uncover performance trends across regions and products, using **Python, Pandas, Matplotlib, and Plotly**.  
It also includes **forecasting future sales** using a simple linear model — demonstrating data-driven decision-making skills.

---

### ⚙️ Tools & Libraries
- **Python**
- **Pandas** — data cleaning and aggregation  
- **Matplotlib & Seaborn** — static visualizations  
- **Plotly Express** — interactive charts  
- **NumPy** — numerical operations  

---

### 📂 Dataset
The dataset (`sales_data.csv`) contains:
| Column | Description |
|---------|-------------|
| Date | Date of sale |
| Region | Sales region (North, South, East, West) |
| Product | Product category |
| Units Sold | Number of units sold |
| Unit Price | Price per unit |
| Sales | Total revenue (calculated as Units × Price) |

---

### 📈 Key Analysis Performed
- **Monthly sales trend** to track growth and dips  
- **Regional sales comparison** to identify high-performing regions  
- **Top-selling products** by revenue contribution  
- **Interactive visualizations** using Plotly  
- **Sales forecasting** using simple regression  

---

### 🪄 Insights
- Sales peaked in January and slightly declined in February.  
- The **West region** consistently achieved the highest sales.  
- **Product A** contributed the most to overall revenue.  
- Forecasting predicts a gradual dip if current trends continue — indicating the need for a marketing push.

---

### 📊 Visualizations
1. **Sales by Region and Product (Bar Chart)**  
2. **Monthly Sales Trend (Interactive Line Chart)**  
3. **Sales Forecast (Line Chart)**  

---

### 🧾 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/sales-performance-analysis.git
   cd sales-performance-analysis
   
2. Install dependencies

       pip install pandas matplotlib plotly numpy
   
3.Open the notebook

      jupyter notebook Sales_Performance_Analysis_Level4.ipynb
