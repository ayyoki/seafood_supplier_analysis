![Preview](https://i.ibb.co/x8nZXBV/your-image.jpg)

# Data Description

- **Rows:** 64,998
- **Columns:** 9

> **Note:** Some data, such as `Manager`, `Buyer`, and `Product Name`, have been replaced with wildcards due to sensitivity.

---

## Data Preprocessing Steps in Power Query

Data preprocessing follows this algorithm, with steps applied as needed:

1. **Data Type Checks and Replacements**
2. **Column Error and NaN Value Checks**
   - Assess data distribution (e.g., check if it follows a normal distribution).
   - Select appropriate method to fill missing numeric values based on distribution (Mean or Median).
3. **Filling Missing Values**
   - **Numeric Values:** Mean/Median
   - **Categorical Values:** Mode
4. **Unique Categorical Value Checks and Replacements**
5. **Removal of Duplicate Values**

---

## Insights from the Data

### Sales and Trends

- **Sales Peak:** Highest sales reached UAH 4.459 million on March 1-2, likely due to high demand in the HoReCa segment (hotels, restaurants, cafes) before International Women's Day.
- **Seasonal Decline:** February sales dropped as people reduced spending after the winter holidays.

### Regional Changes in Demand

- **Increased Demand (Feb-Mar):** Kyiv (+3.8 million UAH) and Odesa (+3.5 million UAH).
- **Decreased Demand (Mar-Apr):** Kyiv (-2.2 million UAH) and Odesa (-1.5 million UAH), while Lviv saw an increase (+2 million UAH).
- **Regional Leader:** Kyiv consistently has the highest sales volumes.
- **Impact of Days of the Week:** No statistically significant effect on sales.

### Product Analysis

- **Top Product:** Product `G_5` leads in sales volume and ranks seventh in units sold.
- **The best-selling product by quantity:** Product `F_0`  has the highest number of sales.
- **Least Successful Product:** Product `H_5` has the lowest sales volume (UAH 1.9 million) and ranks last in popularity (5,837 units).
- **Product Category Performance:** The sales difference between the least (8.9%) and most profitable category (Category 9 with 10.7%) is UAH 6.4 million.
- **Customer Spending Differences:** For example, the most buying Customer `Д` contributed 20.58% and the least  buying Customer `В` 19.38% to total sales, a difference of UAH 4.32 million.
- **Manager Analysis:** Minimal difference in relative sales performance among managers.

### Product Popularity Among Customers

**Top 5 Products by Sales Amount for Each Customer:**

- **Customer A:** G_5, D_9, C_2, A_4, I_8
- **Customer Б:** I_6, A_5, D_5, G_5, H_2
- **Customer В:** A_5, H_2, I_6, B_3, F_9
- **Customer Г:** G_5, I_8, A_5, J_4, G_3
- **Customer Д:** H_2, J_1, I_6, G_3, G_5

**Common Products Across Customers:**

- **G_5** – Purchased by Customers А, Б, Г, Д
- **A_5** – Purchased by Customers Б, В, Г
- **I_6** – Purchased by Customers Б, В, Д
- **H_2** – Purchased by Customers Б, В, Д
- **I_8** – Purchased by Customers А, Г
- **G_3** – Purchased by Customers Г, Д

**Least Popular Products per Customer:**

- **Customer A:** H_5 (326,000 UAH)
- **Customer Б:** A_1 (352,000 UAH)
- **Customer В:** H_5 (375,000 UAH)
- **Customer Г:** H_4 (404,000 UAH) 
- **Customer Д:** H_5 (413,000 UAH)

**Recommended distribution of the worst-selling products among customers:**

- **H_5** for Customer Д
- **A_1** for Customer Д
- **H_4** for Customer Б
---

### Demand for Goods

**Highest Growth in Demand from February to March:**

- D_2 (+89%)
- C_2 (+89%)
- E_2 (+62%)
- B_8 (+54%)
- E_4 (+46%)

**Products Without Demand Growth (Feb 28 - Mar 3):**

- F_4, F_5, G_0, G_4, G_5, J_3

---

### Factors Influencing Price

The Key Influences analysis indicates that **only the product category and name** impact price. Further data may be needed for a more in-depth analysis.
