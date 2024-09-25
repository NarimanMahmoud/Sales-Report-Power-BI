# Sales Report Dashboard: Sales, Customer behavior, and Category Performance Insights
🔗 [View the Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjU5OTI4MDgtNmRiNi00MDY3LWI3MWQtZGI3ZGU1NGVhOTA5IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

During this project, I developed a comprehensive **Sales Performance Dashboard** that offers insights into **sales trends, customer behavior, and product performance.** A custom data model was also designed to optimize the report and enable robust data analysis. Below is an overview of the key components and insights derived from this project.

## 📈 Sales Analytics Dashboard
 **Total Sales Overview**: The dashboard provides an overall view of key metrics such as:

- **Total Sales**: $109.85M
- **Total Freight**: $3.18M
- **Total Tax**: $10.19M
- **Total Due**: $123.22M
- **Total Orders**: 31K
These metrics help track the company’s revenue, orders, and operational costs.

**Order Flag Analysis**: Orders were broken down by Online **(12.1%)** and Offline **(87.9%)**, highlighting the significance of offline sales for the business.

**Shipping Method Performance**: Orders were distributed across various shipping methods, with **XRO Truck Ground and Cargo Transport 5** being key methods. This information informs logistical decisions and optimizations for shipping efficiency.

## 📊 Category, Subcategory and Product Analysis

**Sales by Category**:
Sales were divided across major categories such as Accessories, Bikes, Clothing, and Components.
The dashboard shows that **Bikes** contributed the most to overall sales, accounting for **34.52%** of the total amount due.

**Customer Purchase Patterns**:
Analyzed total sales by weekdays, with **72.26%** of orders placed on weekdays, indicating higher customer activity during the working week.

**Top Products and Subcategories**:
A detailed analysis of sales by products shows **Bike Racks, Helmets, and Water Bottles** as top-performing items, contributing significantly to overall revenue.

**Subcategory Breakdown**:
The dashboard highlights the contribution of different subcategories to the overall sales, enabling product managers to focus on high-revenue items for promotional strategies.

## 🌎 Geographic Sales Insights

**Sales by Region**:
The Total Orders by Territory visual showed the highest sales coming from the **Southwest, Canada, and the Northwest region**, helping to pinpoint key markets for expansion and marketing focus.

**Total Due by Region**:
This analysis further broke down the amount due by region, offering insights into areas where customers tend to have higher outstanding balances or larger purchase volumes.


## 🛠 Data Model Structure

The data model used in this report was custom-built to streamline the relationship between fact and dimension tables. The relationships provide a foundation for deeper analysis of sales data:

**Fact Table**:

- **OrderDetail (Fact)**: Contains transactional details such as order date, product, freight, and order quantities.
**Dimension Tables**:

- **Territory_Dim**: Stores information about different sales territories, including costs and sales data.
- **Product_Dim**: Provides detailed information about products, including categories, product lines, and pricing.
- **ShipMethod_Dim**: Details different shipment methods used for orders.
- **SalesReason_Dim**: Captures reasons behind sales decisions, offering insight into customer behavior.
- **Date_Dim**: Contains date hierarchy (year, month, day) for accurate time-based analysis.
This structured data model enhances report performance and enables powerful, multi-dimensional analysis of sales data, customer retention, and product performance.

🔗 ![Screenshot 2024-09-12 112152](https://github.com/user-attachments/assets/fb5ee9c0-ccd3-4e7e-80c5-6b431282661c)
