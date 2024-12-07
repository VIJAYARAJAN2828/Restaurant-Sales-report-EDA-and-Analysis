# Restaurant Sales Report

**Exploratory Data Analysis (EDA) and Analysis Ideas for Restaurant Business**

## File Description
- **File Format:** CSV  
- **Columns:**  
  - Includes fields like `order_id`, `date`, `item_name`, `item_type`, `item_price`, `quantity`, `transaction_amount`, `transaction_type`, `received_by`, and `time_of_sale`.  
- **Data Size:** 1000 rows and 10 columns.  
- **Data Structure:**  
  - Organized as a single CSV file providing transaction details for a local restaurant.  
- **Data Cleaning and Preprocessing:**  
  - Duplicates and missing values were addressed to ensure data quality.  
- **Last Update:** March 31, 2023.  
- **Special Notes:**  
  - The `transaction_amount` column is calculated as `item_price * quantity`.  
- **Data Source:**  
  - Data collected from a local restaurant for analysis and educational purposes.

## Dataset Description
The dataset captures sales transactions from a local restaurant, offering insights into daily operations and customer behavior. Key details include:  
- **Order Details:** Unique ID, date, and item-level specifics.  
- **Item Information:** Food and beverage names, categories (`Fastfood` or `Beverages`), and pricing.  
- **Transaction Data:** Quantities, total transaction amounts, and payment methods (`cash`, `online`, or others).  
- **Staff Information:** Gender of the individual handling the order.  
- **Timing:** Time of sale categorized as `Morning`, `Afternoon`, `Evening`, `Night`, or `Midnight`.

### Columns
1. `order_id`: Unique identifier for each order.  
2. `date`: Date of the transaction.  
3. `item_name`: Name of the food or beverage.  
4. `item_type`: Category (`Fastfood` or `Beverages`).  
5. `item_price`: Price per unit of the item.  
6. `quantity`: Quantity ordered.  
7. `transaction_amount`: Total amount paid (`item_price * quantity`).  
8. `transaction_type`: Payment method (`cash`, `online`, or others).  
9. `received_by`: Gender of the staff handling the transaction.  
10. `time_of_sale`: Time of day (e.g., `Morning`, `Evening`).

---

## Steps Performed in the Notebook
1. **Library Import and Dataset Loading:**  
   - Used libraries like `pandas`, `numpy`, and `matplotlib` for analysis and visualization.

2. **Data Cleaning and Preprocessing:**  
   - Addressed missing values and duplicates to ensure accurate results.

3. **Exploratory Data Analysis (EDA):**  
   - Analyzed trends in sales, popular items, and time-based behavior.  
   - Insights into payment methods and transaction types.

4. **Visualization:**  
   - Created plots to depict customer behavior and restaurant trends visually.
