# AMAZON-SALES-ANALYSIS-
## 📁 Project Description

The notebook explores and visualizes Amazon sales data to uncover:

- Fulfillment methods (Amazon vs Merchant)
- Product category and sub-category performance
- Monthly sales and order trends
- Revenue contribution by product and region (state)
- Top revenue-generating products and categories

This analysis helps understand how sales, geography, and product types impact overall performance on the Amazon platform.

---

## 📂 Dataset

The dataset used in this project includes the following fields:

- `Product Name`
- `Fulfilment`
- `Category` and `SubCategory`
- `Selling Price`
- `Order Date` and `Shipment Date`
- `State`
- `Quantity`
- `Revenue`

> 📌 The dataset is loaded from a CSV file using Pandas.

---

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📈 Key Insights

- **Fulfillment Distribution**:
  - Nearly **100% of orders were fulfilled by merchants**, with almost no orders fulfilled directly by Amazon.

- **Monthly Trend Analysis**:
  - **July** and **November** were the **peak months for sales**, indicating possible festive season boosts.
  - **December** saw a drop in revenue and order count.

- **Top Performing Categories**:
  - **Mobiles & Accessories** was the most ordered and revenue-generating category.
  - Other significant categories include **Computers & Accessories** and **Home & Kitchen**.

- **Top Revenue-Generating States**:
  - **Maharashtra** and **Karnataka** topped the revenue charts.
  - **Delhi**, **Tamil Nadu**, and **Uttar Pradesh** followed closely.

- **Highest Revenue Products**:
  - Smartphones like **Samsung Galaxy**, **Redmi Note**, and **iPhone** models were top contributors to total revenue.

- **Order Quantity vs Revenue**:
  - Some products had high order quantities but low total revenue due to their lower prices.
  - High-value electronics contributed most to revenue despite lower quantities.

- **Sub-category Trends**:
  - Popular sub-categories include **Smartphones**, **Chargers**, and **Headphones**, especially under high-performing parent categories.
