# Dynamic-Retail-Dashboard
The Dynamic Retail Dashboard is an interactive and data-driven tool built in Excel to visualize and analyze retail data. It connects to datasets hosted on GitHub, uses Power Query for data transformation, and presents insights through dynamic charts and KPIs. The dashboard solves key business questions, enabling informed decision-making.

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
