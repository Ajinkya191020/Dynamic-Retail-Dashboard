# Dynamic-Retail-Dashboard
The primary goal of this project is to develop a comprehensive and dynamic dashboard for analyzing retail data. By leveraging various KPIs and visualizations, the dashboard aims to provide insights into sales performance, profitability, product trends, and return analysis. This project is designed to facilitate better decision-making for retail managers and stakeholders by presenting key metrics in an intuitive and interactive way.


## Datasets Used

### 1. **Orders Table**
The Orders table contains details of customer orders, including product, shipping, and financial metrics.

**Sample Data:**
| Order ID       | Returned | Order Date   | Ship Date   | Ship Mode       | Customer Name   | Segment    | Country         | Market | Sales   | Profit   | Discount |
|----------------|----------|--------------|-------------|-----------------|-----------------|------------|-----------------|--------|---------|----------|----------|
| CA-2012-124891 | No       | 31-07-2020   | 31-07-2020  | Same Day        | Rick Hansen     | Consumer   | United States   | US     | 2309.65 | 762.18   | 0        |
| IN-2013-77878  | Yes      | 05-02-2021   | 07-02-2021  | Second Class    | Justin Ritter   | Corporate  | Australia       | APAC   | 3709.40 | -288.77  | 0.1      |
| IN-2013-71249  | No       | 17-10-2021   | 18-10-2021  | First Class     | Craig Reiter    | Consumer   | Australia       | APAC   | 5175.17 | 919.97   | 0.1      |

### 2. **Returns Table**
Tracks orders that have been returned, along with the associated markets.

**Sample Data:**
| Returned | Order ID         | Market         |
|----------|------------------|----------------|
| Yes      | MX-2013-168137   | LATAM          |
| Yes      | US-2011-165316   | LATAM          |
| Yes      | ES-2013-1525878  | EU             |
| Yes      | CA-2013-118311   | United States  |

### 3. **People Table**
Contains details about sales representatives and their respective regions.

**Sample Data:**
| Person              | Region          |
|---------------------|-----------------|
| Anna Andreadi       | Central         |
| Chuck Magee         | South           |
| Kelly Williams      | East            |
| Matt Collister      | West            |
| Deborah Brumfield   | Africa          |

---

## Problem Statements Solved with Steps

### 1. **Key Performance Indicators (KPIs)**
 

![image](https://github.com/user-attachments/assets/5b2c22d8-01ce-4d52-bdf0-f557c4b2f05e)


---

### 2. **Sales and Profit Analysis**
 
![image](https://github.com/user-attachments/assets/aeb7470f-c874-492e-99da-fd0dae98a215)


---

### 3. **Category-Wise Profit**
 
![image](https://github.com/user-attachments/assets/054c81fc-986f-4822-a5b8-19e64e5a74f1)


---

### 4. **Segment-Wise Sales Share (%)**

![image](https://github.com/user-attachments/assets/31f87c32-45d6-4f81-bf2d-20180df65e15)

---

### 5. **Sales by Country**
 
![image](https://github.com/user-attachments/assets/2935fe8e-078d-4b63-a8e4-380c9f9e01f0)

---

### 6. **Top 5 Subcategories**
  
![image](https://github.com/user-attachments/assets/92e7a17b-ceae-4e6d-9397-4702632a4463)

---

### 7. **Bottom 5 Subcategories**
  
![image](https://github.com/user-attachments/assets/05d9f707-b30d-40fd-9b24-579653bacb3c)

---

### 8. **Yearly Sales Trends**
 

![image](https://github.com/user-attachments/assets/89bf9ee2-3a59-47ef-bbc9-5ea52dd89752)


---

### Next Steps
The future enhancements for this project include:

- **Return Analysis**: Explore the reasons behind returns and analyze trends across markets.
- **Top and Bottom Customer Analysis**: Identify key customers and those requiring engagement strategies.
- **Segment Analysis**: Deep dive into customer segments to tailor marketing and sales strategies.
- **Market Analysis**: Compare sales and returns across different markets to optimize regional performance.
- **Product Analysis**: Examine product-level performance to optimize inventory and pricing strategies.

## KPI Metrics
A dynamic KPI table was created to streamline the dashboard’s metrics:

| Name               | Metric                 | Symbol |
|--------------------|------------------------|--------|
| Total Sales        | Sum of Sales           | 💰     |
| Total Profit       | Sum of Profit          | 📈     |
| Total Quantity     | Sum of Quantity        | 📦     |
| No of Orders       | Count of Order ID      | 🛒     |
| Profitability      | Sum of Profitability   | 💹     |
| Average Discount   | Average of Discount    | 🔍     |

## Steps to Create the Dashboard

1. **Set Up Your Environment**:
   - Choose a data analysis and visualization tool such as **Tableau**, **Power BI**, or **Python** with **Plotly/Dash**.
   - Prepare your **development environment** by installing necessary libraries or software.
   - Load the **Orders**, **People**, and **Return** datasets into your environment.

2. **Data Cleaning and Preparation**:
   - Ensure that each dataset is **cleaned** for null values, duplicates, and formatting inconsistencies.
   - **Join** the three tables as needed, such as using `Order ID` to match returns data with orders.
   - Create derived fields like **Total Profit**, **Profit Margin**, and **Sales Contribution**.

3. **KPI Calculation**:
   - Calculate **Total Sales**, **Total Profit**, **Total Quantity**, **Number of Orders**, and **Average Discount**.
   - Summarize these metrics in a **KPI table** to be used in the dashboard.

4. **Data Visualization**:
   - Create various **charts and graphs**:
     - **Bar Charts** for top and bottom subcategories.
     - **Line Charts** for visualizing the **Yearly Sales Trend**.
     - **Pie Charts** for **Segment-wise Sales Share**.
     - **Geo Maps** for **Sales by Country**.
   - Use **filtering options** to allow users to filter data by **region, market, and customer segment**.

5. **Return Analysis**:
   - Visualize the number of returns across different **markets** and **product categories**.
   - Provide insights into patterns and potential issues causing returns.


## Snapshot of Dashboard

![image](https://github.com/user-attachments/assets/08d41efe-1706-479d-95e9-fd5563b350a2)

---

## Conclusion
The Walmart Dynamic Retail Dashboard provides a comprehensive, real-time view of key retail metrics, enabling better decision-making and faster operational responses. By integrating dynamic elements like interactive charts, slicers, and real-time KPIs, the dashboard empowers users to:

Monitor sales performance across regions, stores, and product categories.

Track inventory levels to optimize stock management and reduce out-of-stock scenarios.

Analyze customer behavior and purchasing trends to fine-tune marketing and promotional strategies.

Identify top-performing and underperforming products, helping drive data-driven merchandising decisions.

Visualize financial health through clear profit, revenue, and cost indicators.

Overall, this dashboard acts as a central command center for Walmart’s retail operations, ensuring leaders have the right insights to maximize efficiency, profitability, and customer satisfaction. The dynamic features allow for flexible data exploration, making it easier for different teams (sales, inventory, finance) to collaborate and act swiftly.
