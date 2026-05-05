# 🛍️ EthnicEdge Store — Annual Sales Report 2022

An Excel-based data analysis project that cleans, processes, and visualizes e-commerce order data for **EthnicEdge Store** — an Indian fashion retailer specializing in ethnic wear, selling across major platforms.

---

## 📁 Project Structure

The workbook contains the following sheets:

| Sheet | Description |
|---|---|
| `EthnicEdge Store` | Raw order data (~31,000+ rows) |
| `Data cleaning` | Cleaned version of the raw data |
| `Data processing` | Enriched data with `Age group` and `Month` columns added |
| `Data analysis` | Pivot tables and summary calculations |
| `sales vs order` | Monthly comparison of total sales amount vs. order count |
| `EthnicEdge store report 2022` | Final annual report summary |
| `men vs women` | Revenue breakdown by gender |
| `order status` | Count of orders by fulfillment status |
| `States` | Top 5 states by total sales amount |
| `age and gender` | Order distribution across age groups and gender |
| `Channel` | Sales share by e-commerce platform |

---

## 📊 Key Insights

- **Total Revenue**: ₹21,100,334
- **Women outspent Men** ~1.8x (₹13.5M vs ₹7.6M)
- **Top State**: Maharashtra (₹2.99M), followed by Karnataka and Uttar Pradesh
- **Best Month**: March (₹1.93M, 2,819 orders)
- **Top Channel**: Amazon (35.5%), followed by Myntra (23.4%) and Flipkart (21.6%)
- **Delivery Rate**: ~92% of orders delivered successfully
- **Age Group**: Adults (26–50) drove the most purchases across both genders

---

## 🧹 Data Cleaning Steps

- Standardized inconsistent `Gender` values (e.g., `"W"`, `"M"` → `"Women"`, `"Men"`)
- Removed leading/trailing whitespace from gender entries
- Dates stored as Excel serial numbers — retained for pivot compatibility

---

## ⚙️ Data Processing

New columns were derived in the `Data processing` sheet:

- **`Age group`** — categorized customers as `Teenager`, `Adult`, or `Senior`
- **`Month`** — extracted month name from the `Date` serial number

---

## 🗂️ Dataset Columns

| Column | Description |
|---|---|
| `Order ID` | Unique order identifier |
| `Cust ID` | Customer identifier |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `Date` | Order date (Excel serial) |
| `Status` | Delivered / Cancelled / Returned / Refunded |
| `Channel` | Sales platform (Amazon, Flipkart, Myntra, etc.) |
| `SKU` | Product SKU code |
| `Category` | Product category (kurta, Set, Saree, Top, etc.) |
| `Size` | Clothing size |
| `Qty` | Quantity ordered |
| `Amount` | Order value in INR |
| `ship-city / ship-state` | Shipping location |
| `B2B` | Whether the order is a business-to-business sale |

---

## 🛠️ Tools Used

- **Microsoft Excel** — data cleaning, pivot tables, charts, and dashboard

---

## 📌 How to Use

1. Open the Excel file in Microsoft Excel
2. Start with the `EthnicEdge Store` sheet for raw data
3. Review `Data cleaning` and `Data processing` for transformation steps
4. Explore the analysis sheets and pivot summaries for insights
5. See `EthnicEdge store report 2022` for the final dashboard

---

## ⚠️ Disclaimer

> This project uses a fictional store name **EthnicEdge Store** for portfolio purposes.
> The dataset used is publicly available and intended for educational and practice use only.
