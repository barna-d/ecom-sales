---

# 📈 Madhav E-commerce Sales Dashboard

An interactive Power BI dashboard designed to provide a comprehensive overview of sales, profit, and customer behavior for a national e-commerce business.

## 📄 Short Description / Purpose

The Madhav E-commerce Sales Dashboard is a strategic tool built for sales managers and business analysts to transform complex sales data into clear, actionable insights. The primary goals are to **identify the most profitable states and cities** and **analyze which product categories are underperforming**. By visualizing key performance indicators (KPIs), the dashboard helps stakeholders track monthly trends, understand customer preferences, and make informed decisions to drive growth and profitability.

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:
*   **📊 Power BI Desktop** – The primary platform used for data modeling, analysis, and report creation.
*   **📂 Power Query** – Utilized for data cleaning, transformation, and merging of the `Orders.csv` and `Details.csv` datasets.
*   **🧠 DAX (Data Analysis Expressions)** – Implemented for creating key calculated measures, including *Sum of Amount*, *Sum of Profit*, and *Average Order Value (AOV)*.
*   **📈 Charts & Visuals** – A combination of bar charts, donut charts, KPI cards, and trend lines to present data intuitively.
*   **✨ Interactive Slicers** – Quarterly and yearly filters to enable dynamic time-based analysis.
*   **📁 Data Source** – CSV files (`Orders.csv`, `Details.csv`).

## 💾 Data Source

**Source:** The project utilizes two core CSV files:
1.  **`Orders.csv`**: Contains order-level data, including `Order ID`, `Order Date`, `CustomerName`, `State`, and `City`.
2.  **`Details.csv`**: Contains financial and product details for each order, including `Amount`, `Profit`, `Quantity`, `Category`, and `Sub-Category`.

The tables were linked in Power BI's data model using the common `Order ID` column, creating a relational model that allows for robust cross-filtering and detailed analysis.

## 🎯 Features / Highlights

*   **Business Problem**
    A national sales manager needs a clear, high-level view of performance to allocate marketing budgets effectively and address profitability gaps. Key questions that are difficult to answer from raw data include:
    *   Which states are driving the most revenue vs. the most profit?
    *   Which product categories sell in high volumes but yield low profits?
    *   Are there specific months where the business is operating at a loss?
    *   Who are our most valuable customers by purchase amount?

*   **Goal of the Dashboard**
    To create a centralized, interactive dashboard that:
    *   Provides at-a-glance monitoring of critical KPIs like total sales, profit, and order volume.
    *   Enables managers to drill down into regional, product, and customer-level performance.
    *   Highlights trends and anomalies to support strategic planning and inventory management.

*   **Walkthrough of Key Visuals**
    *   **KPI Cards (Top Banner)**
        *   **Total Amount**: **438K** in overall revenue.
        *   **Total Profit**: **37K** in net profit.
        *   **Total Quantity**: **5,615** items sold.
        *   **Average Order Value (AOV)**: **121K**, indicating the average revenue per order.
    *   **Sales & Profit by Geography (Bar Charts)**
        *   **Sum of Amount by State**: Highlights **Maharashtra** as the top revenue-generating state.
        *   **Sum of Profit by Sub-Category**: Reveals that **Printers** and **Bookcases** are the most profitable sub-categories.
    *   **Category & Payment Analysis (Donut Charts)**
        *   **Sum of Quantity by Category**: Shows that **Clothing** is the dominant category, accounting for **63%** of all items sold.
        *   **Sum of Quantity by Payment Mode**: Indicates that **Cash on Delivery (COD)** is the most popular payment method at **44%**.
    *   **Profitability Over Time (Column Chart)**
        *   **Profit by Month**: A trendline showing monthly profitability. Critically, it highlights **losses in May, July, September, and December**, with **November** being the most profitable month.
    *   **Customer Insights (Bar Chart)**
        *   **Sum of Amount by Customer Name**: Identifies top customers like **Harivansh** and **Madhav**, who are key targets for loyalty initiatives.

*   **Business Impact & Insights**
    *   **Profitability vs. Volume**: The dashboard reveals a critical insight: **Clothing** drives the highest sales volume (63% of quantity) but is not among the top profit-driving sub-categories. This suggests that the company's highest-volume product line may have low profit margins and requires a strategic review.
    *   **Seasonal Profit Loss**: The business experienced significant profit losses in four separate months. This insight allows managers to investigate the root causes, such as seasonal discounts, high return rates, or increased marketing spend during those periods.
    *   **Regional Focus**: **Maharashtra** is the clear leader in sales. This data supports allocating a larger portion of the marketing budget to this region or analyzing why other states are underperforming.
    *   **Operational Planning**: The high prevalence of **COD (44%)** orders has direct implications for logistics, cash flow management, and the risk of returns. This insight can guide decisions on payment gateway promotions or operational adjustments.

## 📸 Screenshots / Demos

![Dashboard Preview](https://github.com/barna-d/ecom-sales/blob/main/Snapshot%20of%20the%20Dashboard.png)

---

## 👤 Author

Made with ❤️ by **Barna Das**  
🔗 [GitHub Profile](https://github.com/barna-d)

---
