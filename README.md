# Coffee Shop Sales Analysis Project

## **Objective**
The objective of this project is to analyze the retail sales data of a coffee shop chain to uncover actionable insights. By leveraging data cleaning, transformation, and visualization techniques, the analysis aims to:
- Identify sales trends and customer preferences.
- Optimize operational efficiency.
- Provide data-driven recommendations to stakeholders to enhance business performance.

---

## **Problem Statements**
The analysis focuses on addressing the following key business questions:
1. **Sales Trends**: How do sales vary by day of the week and hour of the day? Are there any peak times for sales activity?
2. **Monthly Revenue**: What is the total sales revenue for each month?
3. **Location Performance**: How do sales vary across different store locations?
4. **Customer Spending**: What is the average price/order per person?
5. **Product Insights**: Which products are the best-selling in terms of quantity and revenue?
6. **Category and Type Performance**: How do sales vary by product category and type?

---

## **Process and Methodology**

### **1. Data Cleaning**
- Handled missing or null values in critical fields like `unit_price` and `transaction_qty`.
- Ensured proper data types for columns (e.g., datetime for `transaction_date` and numeric for `unit_price`).
- Removed duplicate records to maintain data accuracy.
- Created new calculated fields such as:
  - **Total Sales**: `transaction_qty * unit_price`.
  - **Hour of Sale**: Extracted from `transaction_time`.

### **2. Data Transformation**
- Segmented data by:
  - **Product Categories** (e.g., Coffee, Tea, Hot Chocolate).
  - **Store Locations** to compare performance.
- Aggregated metrics to analyze:
  - Sales trends by day, month, and hour.
  - Customer purchasing behavior (e.g., average bill per person).

### **3. Dashboard Creation**
Developed an interactive Excel dashboard to present insights. Key features include:
- **KPIs**:
  1. Total Sales
  2. Total Footfall
  3. Average Bill per Person
  4. Average Order per Person
- **Slicers**: Filters for `Month` and `Day of the Week` to enable dynamic analysis.
- **Visualizations**:
  1. **Hourly Sales Trends**: Line chart showing quantity ordered by hour.
  2. **Category Contribution**: Pie chart displaying sales percentage by category.
  3. **Size Distribution**: Bar chart highlighting order preferences by size.
  4. **Store Performance**: Bar chart comparing footfall and sales across store locations.
  5. **Top Products**: Bar chart ranking the top 5 products based on sales.
  6. **Weekday Analysis**: Bar chart showing sales patterns across weekdays.

---

## **Key Takeaways**
- **Customer Behavior**: Coffee dominates sales, with peak activity during mornings and evenings.
- **Sales Trends**: Weekends see higher sales than weekdays, with significant spikes during specific hours.
- **Store Insights**: Urban locations generate the highest revenue and footfall.
- **Product Insights**: Popular products like Espresso and Latte drive significant revenue.

---

## **Suggestions for Stakeholders**
1. **Inventory Management**:
   - Stock up on high-demand products like Coffee during peak hours.
2. **Promotions**:
   - Offer discounts on underperforming items, such as specific teas, during off-peak hours.
3. **Staffing Optimization**:
   - Deploy additional staff during peak times to enhance customer service.
4. **Expansion Opportunities**:
   - Consider opening new stores in high-performing urban areas.
5. **Cross-Selling**:
   - Promote combo deals (e.g., Coffee with a pastry) to increase the average bill per person.

---

## **Tools and Technologies**
- **Data Cleaning and Analysis**: Microsoft Excel
- **Data Visualization**: Excel Dashboards (Interactive slicers, KPIs, and charts)
