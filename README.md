# D-Mart Sales Analysis Project Using Power BI

## 📌 Purpose
This project aims to analyze D-Mart's sales, customer behavior, and inventory data to derive actionable insights and improve operational efficiency.

## 🎯 Objectives
- Gain insights into sales trends and customer purchasing patterns  
- Identify inventory gaps and optimize stock levels  
- Utilize Power BI to create dynamic dashboards for effective decision-making

## 🗂️ Data Sources
- Sales transaction data  
- Customer feedback surveys  
- Inventory reports  
> *Data was exported in CSV and Excel formats from D-Mart’s database.*

## 🧹 Data Preparation
- Cleaned and transformed data for consistency  
- Removed duplicates, handled missing values, and standardized formats  
- Imported data into Power BI for integration and analysis

## 🧩 Data Modeling
- Designed relationships between `Order`, `Customer`, `Location`, and `Product` tables  
- Established one-to-many relationships to ensure seamless data flow  
- Ensured proper key constraints for accurate aggregation and filtering

## 📊 Visualizations Created
- **Gauge Meter**: Displays total discount price  
- **Pie Chart**: Represents order payments based on shipment types  
- **Line Graph**: Tracks inventory levels over time  

## 🔍 Insights Derived

### 🛒 Sales Performance
- Identified peak sales months  
- Recognized best-selling product categories  
- Analyzed year-over-year trends and revenue distribution

### 👥 Customer Insights
- Derived regional preferences and purchasing behavior  
- Gained insights into customer demographics  

### ⚙️ Operational Metrics
- Highlighted underperforming inventory items  
- Measured inventory turnover and shipment efficiency  

## 🧮 Calculated Metrics
- **Selling Price (SP)**: `MRP - Discount Price`  
- **Total Profit**: Summed from the `Product` table  
- **Total Order Value**: `Selling Price × Total Order Quantity`

## ⚠️ Challenges Faced
- Managing large datasets with inconsistent formatting and missing values  
- Establishing relationships between multiple tables with complex structures  
- Writing and optimizing DAX queries for accurate metrics  
- Balancing design aesthetics with visual clarity

## 🛠️ Tools Used
- **Power BI**: For data visualization and insights  
- **Microsoft Excel**: For data cleaning and initial preparation

## 🚀 Future Enhancements
- Automate data updates for real-time dashboard refresh  
- Include predictive analytics to forecast future sales trends  
- Expand scope to include competitor analysis
