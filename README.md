# Sales Forecasting Dataset (Simplified Version)

## 📄 Overview
This dataset simulates 36 months of sales and inventory data for 100 products sold through 45 stores (42 offline and 3 online). It is ideal for time series forecasting, inventory analysis, and demand planning projects.

## 📁 Files Included
1. `sales_data.xlsx` – Monthly sales transactions by product, store, and channel (2021–2023)
2. `store_info.xlsx` – Metadata for all stores including location, type, and platform
3. `stock_availability.xlsx` – Monthly product availability per store
4. `product_info.xlsx` – Category, pricing (offline/online), unit CBM and weights

## 📊 Key Fields

### sales_data.xlsx
| Field       | Description                 |
|-------------|-----------------------------|
| Date        | Month of sale (YYYY-MM)     |
| Store_ID    | Store identifier            |
| Product_ID  | Product identifier          |
| Units_Sold  | Quantity sold               |
| Channel     | Offline or Online           |

### store_info.xlsx
| Field       | Description                      |
|-------------|----------------------------------|
| Store_ID    | Unique store code                |
| Channel     | Offline / Online                 |
| Country     | Country of store (offline only)  |
| State       | State/Province (offline only)    |
| Area_m2     | Area in m² (offline only)        |
| Employees   | Number of staff (offline only)   |
| Platform    | Platform (online only)           |

### stock_availability.xlsx
| Field                   | Description                  |
|--------------------------|------------------------------|
| Date                    | Month (YYYY-MM)              |
| Store_ID                | Store code                   |
| Product_ID              | Product code                 |
| Stock_Availability (%)  | Availability percentage      |

### product_info.xlsx
| Field           | Description                           |
|------------------|---------------------------------------|
| Product_ID       | Product code                          |
| Category         | Product category                      |
| Price_Offline    | Price sold in offline stores (USD)    |
| Price_Online     | Price sold in online stores (USD)     |
| Unit_CBM         | Unit volume (m³)                      |
| Gross_Weight     | Gross weight per unit (kg)            |
| Net_Weight       | Net weight per unit (kg)              |

## 🔍 Use Cases
- Forecast sales by product or store
- Analyze channel performance (offline vs online)
- Correlate stock availability with demand
- Visualize trends and build dashboards

## 🧰 Tools Suggested
- Python (Pandas, Prophet, ARIMA)
- SQL
- Power BI / Tableau

---

This dataset is fully synthetic and intended for educational and portfolio purposes.
