# Data

This folder contains the raw datasets used for the **Excel Sales Dashboard** project.

The datasets were imported into Excel using **Get Data** and then processed and cleaned using **Power Query** before being used for analysis and dashboard creation.

## Datasets

### 1. Products

Contains product-related information used to analyze the products included in the sales data.

**File:** `products.csv`

### 2. Customers

Contains customer-related information used to analyze customer characteristics and purchasing behavior.

**File:** `customers.csv`

### 3. Orders

Contains order and transaction-related information used as the primary source for sales analysis.

**File:** `orders.csv`

## Data Preparation

The datasets were imported into Excel and transformed using **Power Query**. Data preparation included correcting and cleaning the data before using it for further analysis.

The cleaned data was then used to create **Pivot Tables** and build the final Excel dashboard.

## Data Flow

```text
Products
    │
    ├──────────┐
    │          │
Customers   Orders
    │          │
    └────┬─────┘
         ↓
    Power Query
         ↓
 Data Cleaning &
  Transformation
         ↓
    Pivot Tables
         ↓
   Excel Dashboard
```

## Notes

- The files in this folder represent the datasets used as the starting point of the analysis.
- Data cleaning and transformation were performed in Excel Power Query.
- The final analysis and dashboard are available in the `excel/` folder.
