# Supermarket Sales Data Wrangling & Analysis

## 📌 Project Overview
This project focuses on data wrangling and business insights analysis of a **Supermarket Sales dataset**. The dataset was cleaned, processed, and analyzed to extract meaningful insights that can aid decision-making.

## 📊 Dataset Description
- **Source**: Supermarket Sales dataset
- **Rows**: 1006
- **Columns**: 16
- **Key Features**: Sales transactions, customer demographics, product categories, payment methods, and branch performance.

## 🛠 Data Wrangling Process
1. **Handling Missing Values**:
   - Removed rows with missing 'Total' values.
   - Imputed missing values in 'Tax 5%' with the median.
2. **Data Type Standardization**:
   - Converted 'Unit price' to numeric.
   - Converted 'Date' and 'Time' columns to proper datetime format.
3. **Location Data Optimization**:
   - Consolidated separate branch columns into a single 'City' column.
4. **Anomaly Detection and Correction**:
   - Removed duplicate records.
   - Converted negative values in numerical columns to absolute values.

## 📈 Key Business Insights
- **Best-selling product lines**: Health & Beauty and Electronic Accessories.
- **Peak sales periods**: 12 PM - 3 PM, with Fridays being the highest sales day.
- **Most preferred payment method**: E-wallet transactions (45%).
- **Best performing branch**: Yangon, while Naypyitaw shows improvement potential.
- **Customer satisfaction**: Average rating of **7.5/10**, with Electronic Accessories receiving the highest rating.

## 📁 Repository Structure
```
├── Python Project Data - Supermarket Sales and Cleaned_Supermarket_Sales   # Raw and cleaned datasets
├── data_wrangling.ipynb                                                    # Jupyter Notebook with full data wrangling
├── Data Wrangling Report and Business Insights Report                      # PDF reports for data wrangling and business insights
├── README.md	                                                             # Project documentation
```

## 🚀 How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedElmogy25/supermarket-sales-analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd supermarket-sales-analysis
   ```
3. Open the Jupyter Notebook to explore data wrangling steps.

## ✨ Authors & Acknowledgments
- **Author**: [Mohammed Elmogy]
- **Acknowledgment**: Data sourced from the Supermarket Sales dataset.

## 📜 License
This project is open-source and available for educational and research purposes.

